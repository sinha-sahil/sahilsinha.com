<div class="container">
  <img src="images/profilepic.png" alt="" class="profilepic" />
  <div class="subheader">I am</div>
  <div class="header">Sahil Sinha</div>
  <div class="subheader">and I work in</div>
  <div class="header">Software Development & Engineering</div>
  <div class="text">Meanwhile I code this site...</div>
  <div class="text">You can connect with me on following</div>

  <div class="contactItem">
    <img src="images/phone.png" alt="contact" />
    <a href="tel:916205189884">+91-6205189884</a>
  </div>

  <div class="contactItem lastItem">
    <img src="images/email.png" alt="email" />
    <a href="mailto:sahilsinha.dar@gmail.com">sahilsinha.dar@gmail.com</a>
  </div>
</div>

<style>
  .container {
    width: 100vw;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    font-size: 16px;
  }

  .profilepic {
    height: 398px;
    width: 398px;
    margin-bottom: 20px;
  }

  .header {
    color: orange;
    font-size: 32px;
    padding-bottom: 10px;
  }

  .subheader {
    color: white;
    font-size: 20px;
    padding-bottom: 8px;
  }

  .text {
    font-size: 16px;
    color: white;
    padding-bottom: 6px;
  }

  .contactItem {
    display: flex;
    color: white;
    align-items: center;
    margin-top: 8px;
  }

  .contactItem img {
    height: 28px;
    width: 28px;
    margin-right: 8px;
  }

  .contactItem a {
    color: white;
  }

  .lastItem {
    margin-bottom: 20px;
  }

  @media only screen and (max-width: 600px) {
    .header {
      font-size: 18px;
      font-weight: bold;
    }

    .profilepic {
      height: 200px;
      width: 200px;
    }

  }
</style>
