<template>
  <section class="subHead">
    <p>Home / Services</p>
    <h1>Free Checkup</h1>
  </section>
  <section class="singleCard">
    <div class="categories">
      <div>
        <img src="../assets/singleImg/img1.svg" alt="img1" />
        <p>Free Checkup</p>
      </div>
      <div>
        <img src="../assets/singleImg/img2.svg" alt="img1" />
        <p>Cardiogram</p>
      </div>
      <div>
        <img src="../assets/singleImg/img3.svg" alt="img1" />
        <p>Dna Testing</p>
      </div>
      <div>
        <img src="../assets/singleImg/img4.svg" alt="img1" />
        <p>Blood Bank</p>
      </div>
      <div>
        <img src="../assets/singleImg/img3.svg" alt="img1" />
        <p>Dermalogy</p>
      </div>
      <div>
        <img src="../assets/singleImg/img3.svg" alt="img1" />
        <p>Orthopedic</p>
      </div>
    </div>
    <div class="singleCardText">
      <img src="../assets/singleImg/img2.png" alt="" />
      <h2>A passion for putting patients first</h2>
      <div class="singleCardTextCard">
        <div>
          <img src="../assets/singleImg/img5.svg" alt="img5" />
          <p>A Passion for Healing</p>
        </div>
        <div>
          <img src="../assets/singleImg/img5.svg" alt="img5" />
          <p>5-Star Care</p>
        </div>
        <div>
          <img src="../assets/singleImg/img5.svg" alt="img5" />
          <p>A Legacy of Excellence</p>
        </div>
        <div>
          <img src="../assets/singleImg/img5.svg" alt="img5" />
          <p>All our best</p>
        </div>
        <div>
          <img src="../assets/singleImg/img5.svg" alt="img5" />
          <p>A Believe in Us</p>
        </div>
        <div>
          <img src="../assets/singleImg/img5.svg" alt="img5" />
          <p>Always Caring</p>
        </div>
      </div>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
        placerat scelerisque tortor ornare ornare. Quisque placerat scelerisque
        tortor ornare ornare Convallis felis vitae tortor augue. Velit nascetur
        proin massa in. Consequat faucibus porttitor enim et. <br />
        <br />
        <span
          >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque
          placerat scelerisque. Convallis felis vitae tortor augue. Velit
          nascetur proin massa in.</span
        >
      </p>
    </div>
  </section>
  <section class="ourDoctors">
    <p>Meet The</p>
    <h2>Team Members</h2>
    <div class="ourDoctorsCards">
      <div>
        <img src="../assets/singleImg/img3.png" alt="img3" />
        <div class="ourDoctorsCardsCardText">
          <p>Doctor’s Name</p>
          <h6>Neurology</h6>
          <div>
            <img src="../assets//singleImg/linkedin.svg" alt="linkedin" />
            <img src="../assets//singleImg/facebook.svg" alt="ins" />
            <img src="../assets//singleImg/ins.svg" alt="facebook" />
          </div>
        </div>
        <a href="#">View Profile</a>
      </div>
      <div>
        <img src="../assets/singleImg/img4.png" alt="img3" />
        <div class="ourDoctorsCardsCardText">
          <p>Doctor’s Name</p>
          <h6>Neurology</h6>
          <div>
            <img src="../assets//singleImg/linkedin.svg" alt="linkedin" />
            <img src="../assets//singleImg/facebook.svg" alt="ins" />
            <img src="../assets//singleImg/ins.svg" alt="facebook" />
          </div>
        </div>
        <a href="#">View Profile</a>
      </div>
      <div>
        <img src="../assets/singleImg/img5.png" alt="img3" />
        <div class="ourDoctorsCardsCardText">
          <p>Doctor’s Name</p>
          <h6>Neurology</h6>
          <div>
            <img src="../assets//singleImg/linkedin.svg" alt="linkedin" />
            <img src="../assets//singleImg/facebook.svg" alt="ins" />
            <img src="../assets//singleImg/ins.svg" alt="facebook" />
          </div>
        </div>
        <a href="#">View Profile</a>
      </div>
    </div>
    <div class="swiper">
      <img src="../assets//singleImg/img6.svg" alt="img6" />
      <img src="../assets//singleImg/img7.svg" alt="img7" />
      <img src="../assets//singleImg/img6.svg" alt="img6" />
    </div>
  </section>
  <section class="contacts">
    <p>Get in touch</p>
    <h2>Contact</h2>
    <div class="contactsCads">
      <div>
        <img src="../assets/singleImg/img8.svg" alt="img8" />
        <h6>Emergency</h6>
        <p>(237) 681-812-255</p>
        <p>(237) 666-331-894</p>
      </div>
      <div>
        <img src="../assets/singleImg/img9.svg" alt="img9" />
        <h6>Location</h6>
        <p>0123 Some place</p>
        <p>9876 Some country</p>
      </div>
      <div>
        <img src="../assets/singleImg/img10.svg" alt="img9" />
        <h6>Email</h6>
        <p>fildineeesoe@gmil.com</p>
        <p>myebstudios@gmail.com</p>
      </div>
      <div>
        <img src="../assets/singleImg/img11.svg" alt="img9" />
        <h6>Working Hours</h6>
        <p>Mon-Sat 09:00-20:00</p>
        <p>Sunday Emergency only</p>
      </div>
    </div>
  </section>
</template>
<script>
export default {}
</script>
<style scoped>
/*     SubHead    */
.subHead {
  padding: 76px 187px;
  width: 100%;
  height: 250px;
  background-image: url('../assets/singleImg/img1.png');
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.subHead > p {
  font-weight: 400;
  font-size: 18px;
  line-height: 140%;
  color: #1f2b6c;
}
.subHead > h1 {
  font-weight: 400;
  font-size: 48px;
  line-height: 100%;
  color: #1f2b6c;
}

/*    SingleCard    */
.singleCard {
  padding: 60px 187px 128px;
  display: flex;
  align-items: start;
  column-gap: 21px;
}
.categories {
  height: auto;
  border: 1px solid #1f2b6c;
  border-radius: 5px;
}
.categories > div {
  width: 240px;
  display: flex;
  align-items: center;
  column-gap: 8px;
  padding: 24px 32px;
}
.categories > div:first-child {
  background: #1f2b6c;
  color: #bfd2f8;
}
.categories > div:hover,
.categories > div:active {
  background: #1f2b6c;
  color: #bfd2f8;
}
.categories > div > img {
  width: 26px;
  height: 26px;
}
.categories > div > p {
  font-weight: 400;
  font-size: 16px;
  line-height: 140%;
}
.singleCardText > img {
  width: 731px;
  height: 454px;
}
.singleCardText > h2 {
  padding-top: 30px;
  font-weight: 400;
  font-size: 32px;
  line-height: 100%;
  color: #1f2b6c;
}
.singleCardTextCard {
  padding: 24px 0;
  display: flex;
  align-self: center;
  flex-wrap: wrap;
  gap: 16px 10px;
}
.singleCardTextCard > div {
  width: 32%;
  display: flex;
  align-items: center;
  column-gap: 10px;
}
.singleCardTextCard > div > img {
  width: 16px;
  height: 16px;
}
.singleCardTextCard > div > p {
  font-weight: 400;
  font-size: 18px;
  line-height: 140%;
}
.singleCardText > p {
  font-weight: 400;
  font-size: 16px;
  line-height: 140%;
}

/*     ourDoctors       */
.ourDoctors {
  padding: 0px 187px 128px;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.ourDoctors > p {
  font-weight: 700;
  font-size: 18px;
  line-height: 100%;
  letter-spacing: 16%;
  text-transform: uppercase;
  color: #159eec;
}
.ourDoctors > h2 {
  padding-top: 8px;
  font-weight: 400;
  font-size: 32px;
  line-height: 100%;
  letter-spacing: 0%;
  color: #1f2b6c;
}
.ourDoctorsCards {
  padding: 64px 0px 32px;
  display: flex;
  align-items: center;
  column-gap: 20px;
}
.ourDoctorsCards > div {
  width: 317px;
  height: auto;
}
.ourDoctorsCards > div > img {
  width: 317px;
  height: 350px;
}
.ourDoctorsCardsCardText {
  display: flex;
  align-items: center;
  flex-direction: column;
  padding: 24px;
  background: #bfd2f8;
}
.ourDoctorsCardsCardText > p {
  font-weight: 400;
  font-size: 18px;
  line-height: 140%;
  color: #1f2b6c;
}
h6 {
  padding-top: 8px;
  font-weight: 700;
  font-size: 18px;
  line-height: 100%;
  letter-spacing: 16%;
  text-transform: uppercase;
  color: #1f2b6c;
}
.ourDoctorsCardsCardText > div {
  display: flex;
  align-items: center;
  column-gap: 20px;
  padding-top: 16px;
}
ourDoctorsCardsCardText > div > img {
  width: 24px;
  height: 24px;
}
.ourDoctorsCards > div > a {
  padding: 12px 112px;
  background: #1f2b6c;
  color: #bfd2f8;
  border-radius: 0px 0px 8px 8px;
  font-weight: 400;
  font-size: 16px;
  line-height: 140%;
}
.swiper {
  display: flex;
  align-items: center;
  column-gap: 10px;
}
.swiper > img {
  width: 18px;
  height: 18px;
}
/*     Contacts      */
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
