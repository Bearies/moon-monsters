<template>
  <div class="moon-monsters">

    <div class="banner">
      <div class="page-logo">
        <img class="bk-image" src="~/assets/bk_placeholder.png" alt="backgroung image">
        <img class="logo-text" src="~/assets/logo_moonmonsters.png" alt="Moon Monsters">
      </div>
    </div>

    <div class="desc">
      <p class="paragraph">Imagine waking up, on a moon in the middle of spacetime you're surrounded by monsters, and have no memory of exactly how you got here.</p>
      <p class="paragraph">Uncover the mystery and create your own story as a Moon Monster, an intelligent extra-planetary race. As you seek allies and family you build your skills and defenses to stand your ground and explore the new territories you find.</p>
      <p class="paragraph">Each week, venture out into the unknown to discover new secrets, obtain hidden treasures, and defeat a new monster, allowing you to unlock unique items, experiences, and earn MINED tokens.</p>
    </div>

    <div class="video">
      <!-- <iframe width="680" height="400" src="https://www.youtube.com/embed/6Gf_kRE4MJU" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe> -->
    </div>

    <div class="white-paper">
      <button class="whitepaper-btn">READ THE WHITEPAPER</button>
    </div>

    <div class="collaboration">
      <div class="title">in collaboration with</div>
      <div class="logos-row">
        <div class="logos-cell"><img src="~/assets/logo_dispatchlabs.png" alt="Dispatch Labs"></div>
        <div class="logos-cell"><img src="~/assets/logo_playchemy.png" alt="Playchemy"></div>
      </div>
    </div>

    <div id="mc_embed_signup" class="subscription">
      <div class="title">Sign up to get notified when the game is released for IOS and Android.</div>
      <form action="https://moonkidstudios.us18.list-manage.com/subscribe/post?u=863bebef61765efb23c38349f&amp;id=2b435c7848" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <div id="mc_embed_signup_scroll" class="align-center">
          <input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address" required>
          <div style="position: absolute; left: -5000px;" aria-hidden="true">
            <input type="text" name="b_863bebef61765efb23c38349f_9f54197e93" tabindex="-1" value="">
          </div>
          <div class="clear align-center">
            <input type="submit" value="GET UPDATES" name="subscribe" id="mc-embedded-subscribe" class="button">
          </div>
        </div>
      </form>
    </div>

    <footer class="footer">
      <div class="name">Moon Kid Studios</div>
      <div class="email">hello@moonkidstudios.com</div>
    </footer>

  </div>  
</template>

<style scoped>
  .moon-monsters {
    background: #b3feff;
    color: #212121;
  }

  .banner {
    text-align: center;
    height: 100vh;
    width: 100vw;
  }

  .page-logo {
    position: relative;
    display: inline-block;
    height: 100%;
  }
  .bk-image {
    height: 100%;
  }
  .logo-text {
    position: absolute;
    top: 30%;
    left: 10%;
    width: 80%;
  }

  .desc {
    margin: 0 auto;
    padding: 60px 0;
    width: 90%;
    max-width: 780px;
    text-align: center;
    font-family: 'Minecraft', sans-serif;
  }
  .paragraph {
    padding:  15px 0;
    line-height: 2em;
    letter-spacing: .1em;
    color: #424242;
  }
  .paragraph:first-child {
    margin: 0 auto;
    max-width: 520px;
  }

  .video {
    text-align: center;
  }
  
  .white-paper {
    padding: 80px 0;
    text-align: center;
  }
  .whitepaper-btn {
    padding: 1.2em 1.2em .8em;
    background: #fff;
    border: 1px solid #424242;
    font-family: 'Minecraft', sans-serif;
    font-size: 1em;
    letter-spacing: .1em;
    cursor: pointer;
    /* font-family: 'Pix-Riddim', sans-serif; */
  }

  .collaboration {
    padding: 30px 0 40px;
    text-align: center;
  }
  .collaboration .title {
    font-family: 'Minecraft', sans-serif;
    font-size: 1.1em;
    letter-spacing: .1em;
  }
  .logos-row {
    display: flex;
    margin: 10px auto 0;
    width: 100%;
    max-width: 500px;
  }
  .logos-cell {
    padding: 20px;
  }
  .logos-cell img {
    width: 100%;
  }

  .subscription {
    padding: 80px 24px;
    background: #fff;
  }
  .subscription .title {
    margin: 0 auto;
    width: 100%;
    max-width: 360px;
    font-family: 'Minecraft', sans-serif;
    letter-spacing: .1em;
    text-align: center;
    line-height: 1.8em;
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
    font-family: 'Minecraft', sans-serif;
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
    background: #4452e8;
    font-family: 'Minecraft', sans-serif;
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
    background: #fff;
    text-align: center;
    font-size: .9em;
    letter-spacing: .1em;
  }
  .footer .name,
  .footer .email {
    font-family: sans-serif;
    font-weight: 600;
    color: #424242;
  }
  .footer .email {
    margin-top: 6px;
    color: #4452e8;
  }

  @media (max-width: 767px) {
    .moon-monsters {
      padding-top: 10vh;
      padding-bottom: 10vh;
    }
    .banner {
      height: auto;
    }
    .bk-image {
      width: 100%;
    }
  }

/*   @media (min-width: 1440px) {
    .bk-image {
      max-width: 880px;
    }
    .page-logo img {
      max-width: 880px;
    }
  } */
    
/* 
  @media (max-width: 1023px) {
    .page-logo {
      width: 80%;
    }
  }

  

  @media (max-width: 425px) {
    .page-logo img {
      top: 50%;
    }
  } */
</style>