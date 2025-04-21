<template>
	<div class="home">
	  <img width="100%" height="250px" style="margin-bottom: 100px;" src="../assets/serviceImages/SubHead (1).png" alt="">
	</div>
	<div class="services-section">
	  <div class="card-grid">
		<div
		  v-for="(image, index) in images"
		  :key="index"
		  class="card"
		  :class="{ 'active-card': index === 0 }"
		>
		  <div class="image-container">
			<img :src="image" alt="Service" class="main-image" />
			<div class="overlay" v-if="index === 0"></div>
			<img class="icon-image" src="../assets/serviceImages/Group 204 (1).png" alt="Icon" />
		  </div>
		  <div class="card-body">
			<h2>Free Checkup</h2>
			<p>
			  Lorem ipsum dolor sit amet, consectetur adipiscing Quisque
			  placerat Convallis felis vitae tortor augue. Velit nascetur massa
			  in.
			</p>
			<a href="#" class="learn-more">Learn More →</a>
		  </div>
		</div>
	  </div>
	</div>
  
	<!-- Contact Information Card -->
	<section class="contacts">
    <p>Get in touch</p>
    <h2>Contact</h2>
    <div class="contactsCads">
      <div>
        <img src="../assets/serviceImages/Group 188.png" alt="img8" />
        <h6>Emergency</h6>
        <p>(237) 681-812-255</p>
        <p>(237) 666-331-894</p>
      </div>
      <div>
        <img src="../assets/serviceImages/Group 188.png" alt="img8" />
        <h6>Location</h6>
        <p>0123 Some place</p>
        <p>9876 Some country</p>
      </div>
      <div>
        <img src="../assets/serviceImages/Group 188.png" alt="img8" />
        <h6>Email</h6>
        <p>fildineeesoe@gmil.com</p>
        <p>myebstudios@gmail.com</p>
      </div>
      <div>
        <img src="../assets/serviceImages/Group 188.png" alt="img8" />
        <h6>Working Hours</h6>
        <p>Mon-Sat 09:00-20:00</p>
        <p>Sunday Emergency only</p>
      </div>
    </div>
  </section>
  </template>
  
  <script>
  export default {
	data() {
	  return {
		images: [
		  new URL('../assets/serviceImages/Group 204 (1).png', import.meta.url).href,
		  new URL('../assets/serviceImages/Group 204.png', import.meta.url).href,
		  new URL('../assets/serviceImages/Rectangle 20.png', import.meta.url).href,
		  new URL('../assets/serviceImages/Rectangle 20.png', import.meta.url).href,
		  new URL('../assets/serviceImages/Rectangle 20.png', import.meta.url).href,
		  new URL('../assets/serviceImages/Rectangle 20.png', import.meta.url).href
		],
		icon: new URL('../assets/serviceImages/SubHead (1).png', import.meta.url).href
	  }
	}
  }
  </script>
  
  <style scoped>
  .services-section {
	max-width: 1200px;
	margin: 0 auto;
	padding: 2rem 1rem;
	font-family: sans-serif;
  }
  
  .title {
	text-align: center;
	font-size: 2rem;
	font-weight: 600;
	margin-bottom: 2rem;
  }
  
  .card-grid {
	display: grid;
	grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
	gap: 1.5rem;
  }
  
  .card {
	border: 1px solid #e5e5e5;
	border-radius: 12px;
	overflow: hidden;
	background-color: #fff;
	position: relative;
	transition: 0.3s ease;
  }
  
  .card:hover {
	box-shadow: 0 4px 16px rgba(0, 0, 0, 0.08);
  }
  
  .image-container {
	position: relative;
  }
  
  .main-image {
	width: 100%;
	height: auto;
	display: block;
  }
  
  .icon-image {
	position: absolute;
	bottom: -18px;
	right: 16px;
	width: 80px;
	z-index: 2;
  }
  
  .overlay {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background-color: rgba(13, 28, 91, 0.6);
	z-index: 1;
  }
  
  .card-body {
	padding: 2.5rem 1rem 1rem;
	text-align: left;
  }
  
  .card-body h2 {
	font-size: 1.1rem;
	font-weight: 600;
	margin-bottom: 0.5rem;
  }
  
  .card-body p {
	font-size: 0.9rem;
	color: #444;
	line-height: 1.4;
	margin-bottom: 1rem;
  }
  
  .learn-more {
	font-size: 0.9rem;
	color: #3b82f6;
	font-weight: 500;
	text-decoration: none;
  }
  
  .learn-more:hover {
	text-decoration: underline;
  }
  
  /* Active card style */
  .active-card .overlay {
	display: block;
  }
  .contacts {
  padding: 0px 187px 64px;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.contacts > p {
  font-weight: 700;
  font-size: 18px;
  line-height: 100%;
  letter-spacing: 16%;
  text-transform: uppercase;
  color: #159eec;
}
.contacts > h2 {
  padding-top: 8px;
  font-weight: 400;
  font-size: 32px;
  line-height: 100%;
  letter-spacing: 0%;
  color: #1f2b6c;
}
.contactsCads {
  padding-top: 64px;
  display: flex;
  align-items: center;
  column-gap: 20px;
}
.contactsCads > div {
  width: 233px;
  height: 233px;
  padding: 56px 18px 50px 30px;
  background: #bfd2f8;
  border-radius: 5px;
}
.contactsCads > div > img {
  width: 40px;
  height: 38px;
}
.contactsCads > div > h6 {
  padding: 14px 0px 8px;
  font-weight: 700;
  font-size: 18px;
  line-height: 100%;
  text-transform: uppercase;
  color: #1f2b6c;
}
.contactsCads > div > p {
  font-weight: 400;
  font-size: 16px;
  line-height: 140%;
}
.contactsCads > div:nth-child(2) {
  background: #1f2b6c;
  color: #bfd2f8;
}
.contactsCads > div:hover,
.contactsCads > div:active {
  background: #1f2b6c;
  color: #bfd2f8;
}
  </style>