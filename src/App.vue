<template>
    <main :class="$style.main">
      <div :class="$style.containerBg">
        <div :class="$style.containerOverlay">
          <nav :class="$style.nav">
            <ul :class="$style.navUl">
              <li :class="$style.navLi">How it works</li>
              <li :class="$style.navLi">Contact Us</li>
              <li><img :class="$style.navLiImg" src="/brandbrinstagram.svg"  alt="socialIcons" /></li>
              <li><img :class="$style.navLiImg" src="/brandbrlinkedin.svg" alt="socialIcons" /></li>
              <li><img :class="$style.navLiImg" src="/brandbrtwitter.svg"  alt="socialIcons" /></li>
            </ul>
              <img src="/mask-group@2x.png" alt="logo" :class="$style.navLogo"/>
            <div :class="$style.navBtnDiv">
              <button :class="$style.navLogin">Login</button>
              <button :class="$style.btnprimary">join Beta</button>
            </div>
          </nav>
          <section :class="$style.hero">
            <h1 :class="$style.heroheader">
                Empowering Voices, Fuelling Creativity
            </h1>
            <p :class="$style.heroPara">Sponsorrdotcom helps you ignite movements, showcase creativity, recieve donations and raise funding for your business or social causes</p>
            <div :class="$style.heroBtndiv">
              <button :class="$style.btnprimary">join Beta</button>
              <button :class="$style.btnsecondary">Learn More</button>
            </div>
          </section>
        </div>
        
      </div>
      <section :class="$style.about">
        <h2 :class="$style.aboutheader">Sponsorrdotcom</h2>
        <p :class="$style.aboutpara">
            Step into the vibrant world of Sponsorrdotcom, where Nigerian
            influencers and social media personalities find their voices amplified and their dreams empowered. We're more than just a platform; we're a global community united by the belief that your influence can ignite real change. Create campaigns that inspire in categories like arts,tech & design, film & photography, and music, connecting with backers who share your vision. Beyond financial support, Sponsorrdotcom offers a network of empowerment, collaboration, and celebration. With a reach that transcends borders, we're here to turn your aspirations into meaningful impact, one campaign at a time. Join Sponsorrdotcom today and embrace a journey where your influence transforms lives.
        </p>
        <div :class="$style.aboutImgDiv">
          <img :class="$style.aboutImg" src="/red-heart@2x.png" alt="heart"/>
          <img :class="$style.aboutImg" src="/clapping-hands-medium-dark-skin-tone@2x.png" alt="hands" />
          <img :class="$style.aboutImg" src="/hundred-points@2x.png" alt="100" />
        </div>
      </section>
      <section :class="$style.works">
        <h2 :class="$style.worksheader">How it works</h2>
        <div :class="$style.workscontainer"> 
          <div :class="$style.work">
            <img :class="$style.workImg" src="/rocket@2x.png" alt="rocket" />
            <h3 :class="$style.workheader">Launch Your Campaign</h3>
            <p :class="$style.workpara">
              Kickstart your journey by crafting a compelling campaign on Sponsorrdotcom. Present your aspirations, objectives, and the transformative impact you aim to achieve. No matter if it's a social cause, artistic endeavor, or entrepreneurial pursuit, your campaign serves as the platform to inspire support</p>
          </div>
          <div :class="$style.work">
            <img :class="$style.workImg" src="/globe-showing-europe-africa@2x.png" alt="globe" />
            <h3 :class="$style.workheader">Garner Global Support</h3>
            <p :class="$style.workpara">
              Harness the potential of a worldwide audience. As individuals resonate with your mission, they can contribute funds to your campaign, translating their belief in your cause into tangible action. Witness your influence expand as your dreams start to materialize.</p>
          </div>
          <div :class="$style.work">
            <img :class="$style.workImg" src="/flexed-biceps-medium-dark-skin-tone@2x.png" alt="muscle" />
            <h3 :class="$style.workheader">Power Your Impact</h3>
            <p :class="$style.workpara">
              With the funds you've garnered, bring your dreams to fruition.Whether you're creating change within your community or reaching an international stage, Sponsorrdotcom is your springboard. Share progress updates, engage with your supporters, and witness how your influence triggers positive transformations.t</p>
          </div>
        </div>
        <div :class="$style.workbtnDiv">
          <button :class="$style.btnprimary">Join Beta</button>
        </div>
      </section>
      <section :class="$style.categories">
        <h2 :class="$style.categoriesHeader">Categories</h2>
        <div :class="$style.categoriescontainer">
          <div :class="$style.category">
            <img :class="$style.categoryImg" src='/artist-palette@2x.png' alt='art' />
            <h3 :class="$style.categoryheader">Arts</h3>
            <p :class="$style.categorypara">
              Unleash your creativity and showcase your artistic brilliance in this category. Whether you're a painter, sculptor, or mixed media artist, this is where you can gather support for you innovative projects that bring beauty and emotion to life</p>
            <div :class="$style.categorybtnDiv">
              <button :class="$style.btnprimary">Join Beta</button>
            </div>
          </div>
          <div :class="$style.category">
            <img :class="$style.categoryImg" src='/technologist-medium-skin-tone@2x.png' alt='technology' />
            <h3 :class="$style.categoryheader">Tech and Design</h3>
            <p :class="$style.categorypara">
              Dive into the world of technology and design innovation. Whether you're developing apps, designing user interfaces, or engineering groundbreaking solutions, this category provides the platform to fund your technological visions that shape the future.</p>
            <div :class="$style.categorybtnDiv">
              <button :class="$style.btnprimary">Join Beta</button>
            </div>
          </div>
        </div>
        <div :class="$style.categoriescontainer">
          <div :class="$style.category">
            <img :class="$style.categoryImg" src='/film-projector@2x.png' alt='projector' />
            <h3 :class="$style.categoryheader">Film and Photography</h3>
            <p :class="$style.categorypara">
              Capture moments, tell stories, and evoke emotions through film and photography. Whether you're a filmmaker, cinematographer, or a passionate photographer, this category is where your cinematic dreams can find the support they deserve.</p>
            <div :class="$style.categorybtnDiv">
              <button :class="$style.btnprimary">Join Beta</button>
            </div>
          </div>
          <div :class="$style.category">
            <img :class="$style.categoryImg" src='/musical-note@2x.png' alt='art' />
            <h3 :class="$style.categoryheader">Music</h3>
            <p :class="$style.categorypara">
              Let your melodies resonate and rhythms reverberate in the music category. Musicians, composers, and vocalists, this is your stage to seek backing for concerts, album production, music videos, and projects that make the world sing.</p>
            <div :class="$style.categorybtnDiv">
              <button :class="$style.btnprimary">Join Beta</button>
            </div>
          </div>
        </div>

      </section>
      <section :class="$style.banner">
        <h3 :class="$style.bannertext">Elevate Your Influence, Ignite Change - Join Sponsorrdotcom Today! <span><img src="/backhand-index-pointing-right-light-skin-tone@2x.png" :class="$style.bannerImg" alt="hand"/></span> </h3>
        <button :class="$style.bannerBtn">Join Beta</button>
      </section>
    </main>
    <footer :class="$style.footer">
      
    </footer>
  </template>
  <script lang="ts">
    import { defineComponent,  } from "vue";
  
    export default defineComponent({
      name: "LandingPage",
    });
  </script>
  <style module>
  /* utilites */
    .btnprimary{
      outline: none;
      border: none;
      border-radius: 1rem;
      background-color: var(--color-orangered-100);
      padding: 0.9rem 2.4rem;
      color: var(--colors-white);
      font: var(--font-noto-sans);
      font-weight: 800;
      font-size: 1rem;
      letter-spacing: 0.01rem;
    }
    .btnsecondary{
      outline: none;
      border: none;
      border-radius: 1rem;
      background-color: var(--color-antiquewhite);
      padding: 0.9rem 2.4rem;
      color: #333;
      font: var(--font-noto-sans);
      font-weight: 800;
      font-size: 1rem;
      letter-spacing: 0.01rem;
    }
    /*  */
    .main{
      color: var(--colors-white);
      font-family: var(--font-noto-sans);
    }
    .containerBg{
      min-height: 45rem;
      background-image: url('../public/rectangle-1@2x.png');
      background-repeat: no-repeat;
      background-position: center;
      background-size: cover;
    }
    .containerOverlay{
      width: 100%;
      min-height: 45rem;
      background-color: rgba(255, 93, 2, 0.30);
    }
    .nav{
      max-width: 90%;
      margin: 0 auto;
      padding-top: 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .navUl{
      display: flex;
      align-items: center;
      column-gap: 1.5rem;
      font-family: var(--font-noto-sans);
      font-size: 1rem;
      font-feature-settings: 'clig' off, 'liga' off;
      font-weight: 800;
    }
    .navLiImg{
      width: 1.5rem;
      height: 1.5rem;
      object-fit: fill;
    }
    .navLogo{
      width: 10.3125rem;
      height: 4.125rem;
    }
    .navBtnDiv{
      display: flex;
      column-gap: 1.25rem;
    }
    .navLogin{
      outline: none;
      border: 2px solid;
      border-color:  var(--color-antiquewhite);
      border-radius: 1rem;
      background-color: transparent;
      padding: 0.9rem 2.4rem;
      color: var(--colors-white);
      font: var(--font-noto-sans);
      font-weight: 800;
      font-size: 1rem;
      letter-spacing: 0.01rem;
    }
    .hero{
      margin-top: 13.66rem;
      display: flex;
      flex-direction: column;
    }
    .heroheader{
      text-align: center;
      font-size: 3rem;
      font-weight: 900;
    }
    .heroPara{
      font-size: 1.25rem;
      font-weight: 500;
      text-align: center;
      letter-spacing: 0.0125rem;
      max-width: 60.5rem;
      padding: 0 1rem;
      margin: 0 auto;
      margin-top: 1rem;
    }
    .heroBtndiv{
      width: fit-content;
      display: flex;
      gap: 1.25rem;
      margin-top: 3.12rem;
      margin-left: auto;
      margin-right: auto;
    }
    .about{
      background-color: var(--color-antiquewhite);
      padding: 8.75rem 6.25rem;
    }
    .aboutheader{
      color: var(--color-orangered-100);
      text-align: center;
      font-size: 2.5rem;
      font-weight: 900;
      font-feature-settings: 'salt' on, 'liga' off;
      letter-spacing: 0.025rem;
    }
    .aboutpara{
      margin-top: 1.25rem;
      color: #333;
      text-align: center;
      font-size: 1.5rem;
      font-weight: 500;
      letter-spacing: 0.015rem;
    }
    .aboutImgDiv{
      margin-top: 1.25rem;
      display: flex;
      justify-content: center;
      gap: 1.5rem;  
    }
    .aboutImg{
      width: 4.5rem;
      height: 4.5rem;
    }
    .works{
      padding: 8.75rem 6.25rem;
      background: linear-gradient(105deg, #55433B 0%, #000 100%);
    }
    .worksheader{
      text-align: center;
      font-weight: 900;
      font-size: 2.5rem;
      font-feature-settings: 'salt' on, 'liga' off;
    }
    .workscontainer{
      margin-top: 2.5rem;
      display: flex;
      column-gap: 3.5rem;
    }
    .work{
      display: flex;
      flex-direction: column;
      justify-content:center;
      align-items: center;
    }
    .workImg{
      width: 4.5rem;
      height: 4.5rem;
      object-fit: fill;
    }
    .workheader{
      margin-top: 2.5rem;
      font-size: 1.5rem;
      font-weight: 700;
      font-feature-settings: 'salt' on, 'liga' off;
      letter-spacing: 0.015rem;
      text-align: center;
    }
    .workpara{
      margin-top: 1rem;
      font-size: 0.875rem;
      font-feature-settings: 'salt' on, 'liga' off;
      text-align: center;
    }
    .workbtnDiv{
      width: fit-content;
      margin: 0 auto;
      margin-top: 2.5rem;
    }
    .categories{
      padding: 8.75rem 6.75rem;
      background: linear-gradient(0deg, #FFF8F3 0%, #FFF8F3 100%);
    }
    .categoriesHeader{
      color: #271811;
      text-align: center;
      font-size: 2.5rem;
      font-weight: 900;
      letter-spacing: 0.025rem;
    }
    .categoriescontainer{
      margin-top: 2.5rem;
      display: flex;
      column-gap: 2.5rem;
      /* align-items: stretch; */
    }
    .category{
      align-self: stretch;
      padding: 2.5rem;
      background: rgba(194, 119, 0, 0.1);
      border-radius: 1.25rem;
      color: var(--color-black);
    }
    .categoryImg{
      width: 2.5rem;
      height: 2.5rem;
      object-fit: fill;
    }
    .categoryheader{
      margin-top: 0.56rem;
      font-size: 1.5rem;
      font-weight: 700;
      letter-spacing: 0.015rem;
    }
    .categorypara{
      margin-top: 0.56rem;
      font-size: 1rem;
      letter-spacing: 0.01rem;
    }
    .categorybtnDiv{
      margin-top: 3.5rem;
    }
   .banner{
    padding: 2.5rem 6.25rem;
    background-color: var(--color-orangered-100);
    display: flex;
    column-gap: 2rem;
    justify-content: space-between;
    align-items: center;
   } 
   .bannertext{
    font-weight: 700;
    letter-spacing: 0.015rem;
    font-size: 1.5rem;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    column-gap: 1rem;
   }
   .bannerBtn{
    outline: none;
    border: none;
    padding: 1rem 2.5rem;
    border-radius: 1.25rem;
    background-color: #060201;
    color: var(--colors-white);
    font-size: 1rem;
    font-weight: 800;
    cursor: pointer;
    min-width: 164px;
   }
   .bannerImg{
    width: 2.5rem;
    height: 2.5rem;
    object-fit: fill;
   }
   .footer{
    width: 100%;
    height: 54.1875rem;
    background: url('../public/showcase-101@3x.png');
    background-repeat: no-repeat;
    background-position: center;
    background-size:cover;
    /* background-color: orange; */
   }
   /* media queries */
   @media screen and (max-width: 980px){
    .nav{
      max-width: 100%;
      justify-content: center;
    }
    .navUl{
      display:none;
    }
    .navBtnDiv{
      display: none;
    }
    .hero{
      margin-top: 9rem;
    }
    .banner{
      flex-direction: column;
      justify-content: center;
    }
    .bannertext{
      text-align: center;
      flex-direction: column;
    }
    .bannerImg{
      transform: rotate(90deg);
    }
    .bannerBtn{
      margin-top: 0.5rem;
    }
    .workscontainer{
      flex-direction: column;
      row-gap: 3rem;
    }
   }
   @media screen and (max-width: 800px){
    .categoriescontainer{
      flex-direction: column;
      row-gap: 2.5rem;
    }
    .category{
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }
    
   }
   @media screen and (max-width: 500px){
    .hero{
      margin-top: 5.02rem;
    }
    .heroheader{
      font-size: 1.5rem;
      letter-spacing: 0.015rem;
    }
    .heroPara{
      font-size: 1rem;
      letter-spacing: 0.01rem;
    }
    .about{
      padding: 5rem 1rem;
    }
    .aboutheader{
      font-size: 1.5rem;
      letter-spacing: 0.015rem;
    }
    .aboutpara{
      font-size: 1rem;
      letter-spacing: 0.01rem;
    }
    .banner{
      padding: 2.5rem 1rem;
    }
    .bannertext{
      font-size: 1.25rem;
      letter-spacing: 0.0125rem;
      row-gap: 1rem;
    }
    .works{
      padding: 5rem 1rem;
    }
    .worksheader{
      font-size: 1.5rem;
      letter-spacing: 0.015rem;
    }
    .workscontainer{
      margin-top: 3.5rem;
      row-gap: 4rem;
    }
    .workheader{
      font-size: 1.25rem;
      letter-spacing: 0.0125rem;
    }
    .workpara{
      font-size: 0.875rem;
      letter-spacing: 0.00875rem;
    }
    .categories{
      padding: 5rem 1rem;
    }
    .categoriesHeader{
      font-size: 1.5rem;
      letter-spacing: 0.015rem;
    }
    .categoryheader{
      font-size: 1.5rem;
    }
    .categorybtnDiv{
      margin-top: 5rem;
    }
   }

  </style>
