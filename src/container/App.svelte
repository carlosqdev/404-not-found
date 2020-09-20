<style>
  :global(body) {
    margin: 0;
    padding: 0;
    background-color: #fff;
  }
  .main {
    margin: 0 auto;
    width: 100%;
    max-width: 300px;
    display: grid;
    grid-gap: 10px;
    grid-template-columns: 1fr;
    grid-template-rows: repeat(4, auto);
    grid-template-areas: "header" "hero" "content" "footer";
  }
  .main .header{
    grid-area: header;
  }
  .main .header h1 {
    font-family: Inconsolata;
    font-size: 24px;
    font-style: normal;
    font-weight: 700;
    line-height: 25px;
    letter-spacing: -0,08em;
    text-align: left;
    color: #333333;
    margin: 20px 0 0 15px;
  }
  .main .hero {
    grid-area: hero;
    text-align: center;
  }
  .main .hero img {
    width: 231px;
    height: 230px;
  }
  .main .content {
    grid-area: content;
  }
  .main .content h2 {
    font-family: Space Mono;
    font-size: 38px;
    font-style: normal;
    font-weight: 700;
    line-height: 71px;
    letter-spacing: -0,035em;
    text-align: left;
    margin: 60px 0 0 15px;
    color: #333333;
}
.main .content p {
  font-family: Space Mono;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: 27px;
  letter-spacing: -0,035em;
  text-align: left;
  margin: 29px 0 0 15px;
  color: #333333;
}
.main .content button {
  font: Space Mono;
  font-weight: 700;
  font-size: 14px;
  line-height: 20,73px;
  width: 216px;
  height: 68px;
  background: #333333;
  color: #fff;
  margin: 91px 0 0 15px;
  outline: none;
}
.main .footer {
  grid-area: footer;
  text-align: center;
  margin: 96px 0 0 0;
}
.main .footer span {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 600;
  font-size: 12px;
  line-height: 17px;
  color: #333333;
}
@media screen and (min-width: 1024px) {
  .main {
    max-width: 1000px;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(3, auto);
    grid-template-areas: "header header" "hero content" "footer footer";
  }
  .main .header h1 {
    margin-top: 10px;
    margin-left: 40px;
  }
  .main .hero {
    margin-top: 50px;
    margin-right: 20px;
  }
  .main .hero img {
    width: 439px;
    height: 347px;
    margin-left: 40px;
  }
  .main .content {
    margin-top: 50px;
    margin-left: 20px;
  }
  .main .content h2 {
    font-size: 50px;
    margin-left: 0;
  }
  .main .content p {
    font-size: 18px;
    line-height: 36px;
    width: 300px;
    margin-left: 0;
  }
  .main .content button {
    margin-top: 50px;
    margin-left: 0;
  }
  .main .footer {
    margin-top: 40px;
  }
  .main .footer span {
    font-size: 14px;
  }
}
@media screen and (min-width: 1440px) {
  .main {
    max-width: none;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(3, auto);
    grid-template-areas: "header header" "hero content" "footer footer";
  }
  .main .header h1 {
    margin-top: 40px;
    margin-left: 77px;
  }
  .main .hero {
    margin-top: 200px;
    margin-right: 45px;
  }
  .main .hero img {
    width: 539px;
    height: 447px;
    margin-left: 77px;
  }
  .main .content {
    margin-top: 200px;
    margin-left: 45px;
  }
  .main .content h2 {
    font-size: 64px;
    margin-left: 0;
  }
  .main .content p {
    font-size: 24px;
    line-height: 36px;
    width: 450px;
    margin-left: 0;
  }
  .main .content button {
    margin-left: 0;
  }
  .main .footer {
    margin-top: 293px;
  }
  .main .footer span {
    font-size: 24px;
  }
}
</style>

<div class="main">
  <header class="header">
    <h1>404 NOT FOUND</h1>
  </header>
  <section class="hero">
    <img src="https://github.com/carlosqdev/404-not-found/blob/master/public/img/Scarecrow.png?raw=true" alt="Espanta pajaro">
  </section>
  <section class="content">
    <h2>I have bad news for you</h2>
    <p>The page you are looking for might be removed or is temporarily unavailable</p>
    <button>BACK TO HOMEPAGE</button>
  </section>
  <footer class="footer">
    <span>Carlos Quintero @ DevChallenges.io</span>
  </footer>
</div>