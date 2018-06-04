<template>
  <div class="moon-monsters">

    <div class="banner">
      <div class="page-logo">
        <img class="bk-image" src="~/assets/images/space-bk.png" alt="backgroung image">
        <img class="logo-text" src="~/assets/images/logo_moonkidstudios-2.png" alt="Moonkidstudios">
      </div>
    </div>

    <div class="desc">
      <p class="paragraph">Moon Kid Studios is a creative Game Dev and Blockchain studio creating a suite of blockchain based games centered around an extraterrestrial world and its many moons. The games allow players to follow the story as it weaves through different interactive environments and collect and buy cryptocurrency and NFTs as they go.</p>
    </div>

    <div class="coming-soon">
      <div class="text-row">
        <div class="monster"><img class="monster-eggs" src="~/assets/images/eggs.png" alt="eggs"></div>
        <div class="text">
          <div class="feature-title">Moon Monsters: XLab</div>
          <p>Humans have discovered a far outpost of alien life.</p>
          <p>Around the Planet Zeta there are in orbit dozens of moons. The moons are inhabited by what appear to us as animal-like life forms. A nest of abandoned eggs has been procured to begin a study. Join the ranks of pioneering Xeno Anthropologists searching for the truth. Are these beings truly intelligent? Can we befriend and teach them? What will be learn?</p>
          <p>Raise a Moon Monster from egg to young adulthood and help record behavioral traits. Care for, Name, and build an environment you believe it will respond to. What do we have on our hands? What are the implications for the Human race?</p>
          <button class="comingsoon-btn">COMING SOON!</button>
        </div>
      </div>
    </div>

    <div class="white-paper">
      <div class="text-row">
        <div class="text">
          <div class="feature-title">Moon Monsters: Mobile</div>
          <p>Imagine waking up, on a moon in the middle of spacetime. You’re surrounded by monsters, and have no memory of exactly how you got there.</p>
          <p>Uncover the mystery and create your own story as a Moon Monster, an intelligent extra-planetary race. As you seek allies and family you build your skills and defenses to stand your ground and explore the new territories you find.</p>
          <p>Each week, venture out into the unknown to discover new secrets, obtain hidden treasures, and defeat a new monster, allowing you to unlock unique items, experiences, and earn MINED tokens.</p>
          <button class="whitepaper-btn">READ THE WHITEPAPER</button>
        </div>
        <div class="monster"><img class="monster-tail" src="~/assets/images/feature2_monster.png" alt="monster"></div>
      </div>
    </div>

    <div id="mc_embed_signup" class="subscription">
      <div class="title">Sign up to get notified about new game releases and updates!</div>
      <form action="https://moonkidstudios.us18.list-manage.com/subscribe/post?u=863bebef61765efb23c38349f&amp;id=2b435c7848" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <div id="mc_embed_signup_scroll" class="align-center">
          <input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address" required>
          <div style="position: absolute; left: -5000px;" aria-hidden="true">
            <input type="text" name="b_863bebef61765efb23c38349f_9f54197e93" tabindex="-1" value="">
          </div>
          <div class="clear align-center">
            <input type="submit" value="SIGN ME UP" name="subscribe" id="mc-embedded-subscribe" class="button">
          </div>
        </div>
      </form>
    </div>

    <footer class="footer">
      <div class="email">moonkidstudios@gmail.com</div>
      <div class="name">Moon Kid Studios © 2018</div>
    </footer>

  </div>
</template>

<style scoped>


  .moon-monsters {
    /* background: linear-gradient(90deg, #101b27, #434e5d); */
    background-color: #101b27;
  }

  @import url('https://fonts.googleapis.com/css?family=PT+Mono');
  font-family: 'PT Mono', monospace;

  .banner {
    text-align: center;
    width: 100vw;
  }
  .page-logo {
    position: relative;
    width: 100%;
  }
  .bk-image {
    width: 100%;
  }
  .logo-text {
    position: absolute;
    top: 30%;
    left: 27%;
    width: 46%;
  }
  .desc {
    padding: 12% 0;
    margin-top: -20%;
    /* background-image: url('~/assets/images/largemoon.png'); */
    background-size: 100%;
    background-position: top center;
    background-repeat: no-repeat;
    color: #fff;
    position: relative;
    z-index: 10;
    font-family: 'PT Mono', monospace;
    font-size: 1.7vw;
    text-align: center;
    text-shadow: .1em .1em black;
    letter-spacing: .1em;
  }
  .feature-title{
    font-size: 2vw;
    margin-bottom: 15px;
  }
  .paragraph {
    margin: 0 auto;
    width: 60%;
    line-height: 1.7em;
  }

  .coming-soon {
    background: #9798b6;
  }
  .white-paper {
    background: #ffbac9;
  }

  .text-row {
    display: flex;
    margin: 0 auto;
    padding: 6% 24px;
    width: 100%;
    max-width: 1200px;
  }
  .monster {
    flex: none;
    width: 30%;
  }
  .coming-soon .monster {
    width: 26%;
  }
  .text-row .text {
    position: relative;
    /* font-family: 'Minecraft', sans-serif; */
    font-family: 'PT Mono', monospace;
    font-weight: 400;
    color: #fff;
    line-height: 1.6em;
    letter-spacing: .1em;
    z-index: 2;
  }
  .white-paper .text {
    color: #424242;
  }

  .coming-soon .text {
    padding-left: 40px;
  }

  .text-row .text p {
    padding:  10px 0;
  }
  .coming-soon .monster,
  .white-paper .monster {
    position: relative;
  }

  .monster-eggs {
    position: absolute;
    bottom: 10%;
    width: 100%;
  }

  .monster-tail {
    position: absolute;
    right: 0;
    bottom: 0;
    width: 100%;
    transform: translate(-30%, -20%)scale(1.6);
  }

  .comingsoon-btn,
  .whitepaper-btn {
    margin-top: 8%;
    padding: 1.2em 1.2em .8em;
    font-family: 'Minecraft', sans-serif;
    font-size: 1em;
    letter-spacing: .1em;
    cursor: pointer;
    opacity: 0;
  }
  .comingsoon-btn {
    background: #00f7ff;
    border: 1px solid #0aa4aa;
    color: #056569;
  }
  .whitepaper-btn {
    background: #fcb0e3;
    border: 1px solid #fe5b96;
    color: #462047;
  }


  .subscription {
    padding: 80px 24px;
  }
  .subscription .title {
    margin: 0 auto;
    width: 100%;
    max-width: 360px;
    /* font-family: 'Minecraft', sans-serif; */
    font-family: 'PT Mono', monospace;
    letter-spacing: .1em;
    text-align: center;
    line-height: 1.8em;
    color: #fff;
  }
  .subscription .item {
    text-align: center;
  }
  .subscription .email {
    margin-top: 30px;
    padding: 20px;
    height: 50px;
    width: 90%;
    max-width: 400px;
    border: 1px solid #424242;
    /* font-family: 'Minecraft', sans-serif; */
    font-family: 'PT Mono', monospace;
    font-size: .8em;
    letter-spacing: .1em;
    text-align: center;
  }
  .subscription .button {
    margin-top: 14px;
    padding-top: .2em;
    height: 50px;
    width: 90%;
    max-width: 300px;
    background: #fe5b96;
    border: 1px solid #fe5b96;
    /* font-family: 'Minecraft', sans-serif; */
    font-family: 'PT Mono', monospace;
    font-size: .8em;
    letter-spacing: .2em;
    text-align: center;
    color: #fff;
    cursor: pointer;
  }
  .align-center {
    text-align: center;
  }

  .footer {
    padding: 20px;
    /* font-family: 'Minecraft', sans-serif; */
    font-family: 'PT Mono', monospace;
    font-size: .9em;
    letter-spacing: .1em;
    text-align: center;
  }
  .footer .name,
  .footer .email {
    font-weight: 500;
    color: #fff;
  }
  .footer .name {
    margin-top: 1em;
    font-size: .8em;
  }
  .footer .email {
    color: #fe5b96;
  }

  @media (max-width: 767px) {
    .desc {
      padding: 15% 0 4%;
    }
    .feature-title{
      font-size: 6vw;
      margin-top: 20px;
    }
    .paragraph {
      width: 90%;
      line-height: 1.8em;
      font-size: 3vw;
    }
    .text-row {
      flex-wrap: wrap;
    }
    .monster {
      flex: none;
      width: 100%;
    }
    .text-row .text {
      flex: none;
      width: 100%;
    }
    .coming-soon .text {
      padding-left: 0;
    }
    .monster-eggs,
    .monster-tail {
      position: static;
    }
    .coming-soon .monster {
      width: 100%;
      text-align: center;
    }
    .monster-eggs {
      width: 50%;
      max-width: 240px;
    }
    .monster-tail {
      margin-top: 20px;
      width: 80%;
      min-width: 260px;
      transform: translate(0, 0)scale(1);
    }
  }
</style>
