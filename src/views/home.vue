<template>
  <div class="home-container">
    <section class="home-hero">
      <div class="home-main">
        <div class="home-content">
          <header data-thq="thq-navbar" class="home-navbar-interactive">
            <app-branding
              rootClassName="branding-root-class-name1"
            ></app-branding>
            <div
              data-thq="thq-navbar-nav"
              data-role="Nav"
              class="home-desktop-menu"
            >
              <div class="home-links">
                <router-link to="/" class="home-link navLink">
                  Mission
                </router-link>
              </div>
            </div>
            <div data-thq="thq-burger-menu" class="home-burger-menu">
              <button class="button">
                <svg viewBox="0 0 1024 1024" class="home-icon">
                  <path
                    d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
                  ></path>
                </svg>
              </button>
            </div>
            <div data-thq="thq-mobile-menu" class="home-mobile-menu">
              <div
                data-thq="thq-mobile-menu-nav"
                data-role="Nav"
                class="home-nav"
              >
                <div class="home-container1">
                  <app-branding
                    rootClassName="branding-root-class-name"
                  ></app-branding>
                  <div data-thq="thq-close-menu" class="home-menu-close">
                    <svg viewBox="0 0 1024 1024" class="home-icon02">
                      <path
                        d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                      ></path>
                    </svg>
                  </div>
                </div>
                <div class="home-links1">
                  <router-link to="/" class="home-link1 navLink">
                    Mission
                  </router-link>
                  <router-link to="/" class="home-link2 navLink">
                    Take Action
                  </router-link>
                  <router-link to="/" class="home-link3 navLink">
                    News
                  </router-link>
                  <router-link to="/" class="home-link4 navLink">
                    Contact
                  </router-link>
                </div>
                <div class="home-icon-group">
                  <svg viewBox="0 0 950.8571428571428 1024" class="home-icon04">
                    <path
                      d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
                    ></path></svg
                  ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon06">
                    <path
                      d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
                    ></path></svg
                  ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon08">
                    <path
                      d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
                    ></path>
                  </svg>
                </div>
              </div>
            </div>
          </header>
          <div class="home-hero-section">
            <div class="home-header">
              <h1 class="home-heading">
                Réparez, Apprenez, Participez!
                <span v-html="raw92ks"></span>
              </h1>
              <p class="home-caption">
                Réparez, Apprenez, Participez! Rejoignez notre communauté de
                Repair Café
              </p>
            </div>
            <div class="home-buttons"></div>
          </div>
        </div>
        <div class="home-image"></div>
      </div>
      <div class="home-details-container">
        <div class="home-details">
          <div class="home-category"></div>
          <div class="home-category1"></div>
          <div class="home-category2"></div>
        </div>
      </div>
    </section>
    <section class="home-mission">
      <div class="home-content1">
        <div class="home-main1">
          <span class="home-title">Nos Missions</span>
          <div class="home-header1">
            <h2 class="home-heading1">
              Les Repair Cafés contribuent à un monde meilleur en promouvant la
              réparation, renforçant les communautés et réduisant les déchets et
              les charges financières pour les ménages
            </h2>
          </div>
        </div>
        <div class="home-highlights">
          <div class="home-highlight">
            <h3 class="home-title1">Réparez</h3>
            <p class="home-description">
              Nous vous aidons à réparer vos objets cassés et à prolonger leur
              durée de vie
            </p>
          </div>
          <div class="home-highlight1">
            <h3 class="home-title2">Apprenez</h3>
            <p class="home-description1">
              Nous voulons également offrir l&apos;opportunité aux gens de votre
              communauté d&apos;apprendre les compétences pratiques de la
              réparation.
            </p>
          </div>
        </div>
      </div>
      <div class="home-images">
        <img
          alt="image"
          src="https://images.unsplash.com/photo-1550041473-d296a3a8a18a?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDEwfHxyZXBhaXJ8ZW58MHx8fHwxNjc0MjA1Mjc4&amp;ixlib=rb-4.0.3&amp;w=400"
          class="home-image1"
        />
        <div class="home-row">
          <img
            alt="image"
            src="https://images.unsplash.com/photo-1611433965582-de98df4da7ce?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDQ0fHxyZXBhaXJ8ZW58MHx8fHwxNjc0MjA1MzI5&amp;ixlib=rb-4.0.3&amp;w=400"
            class="home-image2"
          />
        </div>
      </div>
    </section>
    <section class="home-steps">
      <div class="home-content2">
        <div class="home-information">
          <div class="home-main2">
            <div class="home-header2">
              <h2 class="home-heading2">
                Notre Repair Café est également un lieu où vous pouvez apporter
                vos appareils cassés qui ne peuvent plus être réparés. Nous les
                utiliserons pour pièces détachées pour les réparations futur.
              </h2>
            </div>
          </div>
          <div class="home-button1"></div>
        </div>
        <app-steps></app-steps>
      </div>
    </section>
    <section class="home-quote-one">
      <div class="home-quote-content">
        <h2 class="home-quote">
          &quot;J&apos;ai eu la chance de participer au Repair Café
          &quot;Ingevert&quot; organisé par l&apos;ESIPE et je ne peux pas dire
          assez de bien de cette expérience. Les étudiants et les volontaires
          étaient incroyablement compétents et ont réussi à réparer mon vieux
          appareil photo qui était censé être jeté. J&apos;ai appris beaucoup sur
          la réparation d&apos;appareils électroniques grâce à eux et j&apos;ai
          été impressionné par leur passion pour l&apos;écologie et
          l&apos;éducation. Je recommande vivement ce Repair Café à tous ceux qui
          cherchent à apprendre de nouvelles compétences et à contribuer à une
          cause importante.&quot;
        </h2>
        <div class="home-quoted">
          <img
            alt="pastedImage"
            src="/playground_assets/pastedimage-xcd4-200h.png"
            class="home-pasted-image"
          />
          <p class="home-caption1">El hadge </p>
        </div>
      </div>
    </section>
    <div class="home-donate"></div>
    <section class="home-updates"></section>
    <footer class="home-footer">
      <div class="home-top">
        <app-branding></app-branding>
        <nav class="home-navigation-links">
          <router-link to="/" class="home-link5 navLink">Mission</router-link>
          <router-link to="/" class="home-link6 navLink">Take Action</router-link>
          <router-link to="/" class="home-link7 navLink">News</router-link>
          <router-link to="/" class="home-link8 navLink">Contact</router-link>
        </nav>
      </div>
      <div class="home-middle">
        <span class="home-text">
          +33 6 95430201 andy.libon@edu.univ.eiffel.fr
        </span>
        <span class="home-text1">
          Bâtiment Copernic, 5 Bd Descartes, 77420 Champs-sur-Marne
        </span>
      </div>
      <div class="home-bottom">
        <span class="home-copyright">© Copyright Company – 2022</span>
      </div>
    </footer>
    <div>
      <DangerousHTML
        html="<script>
  const slides = document.querySelectorAll('.slide');
  let currentSlide = 0;
  
  function showSlide(n) {
    slides[currentSlide].classList.remove('slide-active');
    currentSlide = (n + slides.length) % slides.length;
    slides[currentSlide].classList.add('slide-active');
  }
  
  const previousSlideButton = document.querySelector('#previous-slide');
  previousSlideButton.addEventListener('click', () => {
    showSlide(currentSlide - 1);
  });
  
  const nextSlideButton = document.querySelector('#next-slide');
  nextSlideButton.addEventListener('click', () => {
    showSlide(currentSlide + 1);
  });
  </script>"
      ></DangerousHTML>
    </div>
    <div>
      <DangerousHTML
        html="<script>
  function setCookie(name, value, days) {
    // Set the cookie with the given name, value, and expiration time (in days)
    let expires = '';
    if (days) {
      let date = new Date();
      date.setTime(date.getTime() + (days * 24 * 60 * 60 * 1000));
      expires = '; expires=' + date.toUTCString();
    }
    document.cookie = name + '=' + (value || '') + expires + '; path=/';
  }
  
  function getCookie(name) {
    // Get the value of the cookie with the given name
    let nameEQ = name + '=';
    let ca = document.cookie.split(';');
    for (let i = 0; i < ca.length; i++) {
      let c = ca[i];
      while (c.charAt(0) === ' ') c = c.substring(1, c.length);
      if (c.indexOf(nameEQ) === 0) return c.substring(nameEQ.length, c.length);
    }
    return null;
  }
  
  function removeCookie(name) {
    // Remove the cookie with the given name
    setCookie(name, '', -1); // Set the cookie with an expiration time of -1 days
  }
  
  document.getElementById('close').addEventListener('click', function(){
    // Get the persistence value
    let persistence = document.getElementById('banner').getAttribute('data-persistence');
    if (persistence === 'true') {
      // If persistence is enabled, set a cookie to remember that the banner is closed
      setCookie('bannerClosed', 'true', 1); // Set the cookie with an expiration time of 1 day
    } else {
      removeCookie('bannerClosed')
    }
    document.getElementById('banner').style.display = 'none'; // Hide the banner
  });
  
  window.addEventListener('load', function() {
    // Check if the banner should be displayed or not
    let bannerClosed = getCookie('bannerClosed');
    if (bannerClosed === 'true') {
      // If the bannerClosed cookie is set, hide the banner
      document.getElementById('banner').style.display = 'none';
    }
  });
  </script>"
      ></DangerousHTML>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/vue'

import AppBranding from '../components/branding'
import AppSteps from '../components/steps'

export default {
  name: 'Home',
  components: {
    AppBranding,
    AppSteps,
    DangerousHTML,
  },

  data() {
    return {
      raw92ks: ' ',
    }
  },

  metaInfo: {
    title: 'Helpa (Template 7)',
    meta: [
      {
        property: 'og:title',
        content: 'Helpa (Template 7)',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-hero {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  background-color: #F6F5ED;
}
.home-main {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  height: 646px;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-left: var(--dl-space-space-fiveunits);
  flex-direction: row;
}
.home-content {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  height: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
}
.home-navbar-interactive {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  justify-content: center;
}
.home-desktop-menu {
  display: flex;
}
.home-links {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-link {
  text-decoration: none;
}
.home-burger-menu {
  display: none;
  align-items: center;
  justify-content: center;
}
.home-icon {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 100;
  position: fixed;
  flex-direction: column;
  justify-content: space-between;
  background-color: #fff;
}
.home-nav {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-container1 {
  width: 100%;
  display: flex;
  align-items: center;
  padding-bottom: var(--dl-space-space-oneandhalfunits);
  justify-content: space-between;
}
.home-menu-close {
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-icon02 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-links1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  flex-direction: column;
}
.home-link1 {
  text-decoration: none;
}
.home-link2 {
  text-decoration: none;
}
.home-link3 {
  text-decoration: none;
}
.home-link4 {
  text-decoration: none;
}
.home-icon-group {
  display: flex;
}
.home-icon04 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon06 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon08 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-hero-section {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-heading {
  color: rgb(34, 34, 35);
  font-size: 70px;
  font-style: normal;
  font-family: Lora;
  font-weight: 500;
  line-height: 91px;
}
.home-caption {
  color: rgb(34, 34, 35);
  font-size: 20px;
  line-height: 30px;
}
.home-buttons {
  gap: var(--dl-space-space-unit);
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-image {
  flex: 1;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  height: 100%;
  display: flex;
  overflow: hidden;
  align-items: flex-end;
  padding-top: var(--dl-space-space-oneandhalfunits);
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  background-size: cover;
  background-image: url("https://images.unsplash.com/photo-1603771551023-7f0ea70c56d2?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDMzfHxyZXBhaXJ8ZW58MHx8fHwxNjc0MjA1MzI5&ixlib=rb-4.0.3&w=1400");
}
.home-details-container {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
  background-color: #79D490;
}
.home-details {
  gap: var(--dl-space-space-fiveunits);
  flex: 1;
  height: 30px;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: flex-start;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-fourunits);
}
.home-category {
  gap: var(--dl-space-space-twounits);
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-category1 {
  gap: var(--dl-space-space-twounits);
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-category2 {
  gap: var(--dl-space-space-twounits);
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-mission {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: 200px;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-sixunits);
  justify-content: center;
}
.home-content1 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 560px;
  align-items: flex-start;
  flex-direction: column;
}
.home-main1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-title {
  color: rgb(34, 34, 35);
  font-style: normal;
  font-weight: 500;
}
.home-header1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-heading1 {
  color: rgb(34, 34, 35);
  font-size: 40px;
  font-style: normal;
  font-family: Lora;
  font-weight: 500;
  line-height: 52px;
}
.home-highlights {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-highlight {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  max-width: 248px;
  align-items: flex-start;
  flex-direction: column;
}
.home-title1 {
  color: rgb(34, 34, 35);
  font-size: 40px;
  font-style: normal;
  font-family: Lora;
  font-weight: 500;
  line-height: 52px;
  border-color: var(--dl-color-gray-black);
  border-style: dashed;
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-left-width: 1px;
}
.home-description {
  color: rgb(34, 34, 35);
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-highlight1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  max-width: 248px;
  align-items: flex-start;
  flex-direction: column;
}
.home-title2 {
  color: rgb(34, 34, 35);
  font-size: 40px;
  font-style: normal;
  font-family: Lora;
  font-weight: 500;
  line-height: 52px;
  border-color: var(--dl-color-gray-black);
  border-style: dashed;
  padding-left: var(--dl-space-space-oneandhalfunits);
  border-left-width: 1px;
}
.home-description1 {
  color: rgb(34, 34, 35);
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-images {
  flex: 1;
  display: flex;
  position: relative;
  align-items: flex-end;
  flex-direction: row;
  justify-content: space-between;
}
.home-image1 {
  width: 367px;
  object-fit: cover;
}
.home-row {
  display: flex;
  align-items: flex-end;
  flex-direction: row;
  justify-content: space-between;
}
.home-image2 {
  right: 0px;
  width: 333px;
  bottom: 0px;
  z-index: 100;
  position: absolute;
  object-fit: cover;
}
.home-steps {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  background-color: #F6F5ED;
}
.home-content2 {
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: 120px;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: row;
  padding-bottom: 120px;
  justify-content: space-between;
}
.home-information {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 560px;
  align-items: flex-start;
  flex-direction: column;
}
.home-main2 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-header2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-heading2 {
  color: rgb(34, 34, 35);
  width: 496px;
  font-size: 40px;
  font-style: normal;
  font-family: Lora;
  font-weight: 500;
  line-height: 52px;
}
.home-button1 {
  gap: var(--dl-space-space-twounits);
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-quote-one {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 120px;
  flex-direction: column;
  padding-bottom: 120px;
  justify-content: center;
  background-color: #F6F5ED;
}
.home-quote-content {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  justify-content: center;
}
.home-quote {
  color: rgb(34, 34, 35);
  width: 100%;
  font-size: 32px;
  max-width: 900px;
  font-style: italic;
  font-family: Lora;
  font-weight: 500;
  line-height: 48px;
}
.home-quoted {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 900px;
  align-items: center;
  flex-direction: row;
}
.home-pasted-image {
  width: 59px;
  height: 61px;
}
.home-caption1 {
  color: rgb(34, 34, 35);
  font-size: 18px;
  font-style: italic;
  font-family: Lora;
  font-weight: 500;
}
.home-donate {
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: center;
  flex-direction: column;
  background-color: #79D490;
}
.home-updates {
  width: 100%;
  border: 2px dashed rgba(120, 120, 120, 0.4);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  background-color: #E8E6DA;
}
.home-footer {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: 120px;
  padding-left: var(--dl-space-space-fourunits);
  padding-right: var(--dl-space-space-fourunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-threeunits);
  justify-content: center;
  background-color: #79D590;
}
.home-top {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: center;
  border-color: #222223;
  border-style: dashed;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-oneandhalfunits);
  justify-content: center;
  border-bottom-width: 1px;
}
.home-navigation-links {
  gap: var(--dl-space-space-twounits);
  display: flex;
  position: relative;
  align-items: center;
  flex-direction: row;
}
.home-link5 {
  text-decoration: none;
}
.home-link6 {
  text-decoration: none;
}
.home-link7 {
  text-decoration: none;
}
.home-link8 {
  text-decoration: none;
}
.home-middle {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 250px;
  align-items: center;
  padding-top: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-threeunits);
  justify-content: center;
}
.home-text {
  width: 100%;
  font-size: 24px;
  font-style: normal;
  text-align: center;
  font-family: Lora;
  font-weight: 500;
  line-height: 36px;
}
.home-text1 {
  width: 100%;
  font-size: 24px;
  font-style: normal;
  text-align: center;
  font-family: Lora;
  font-weight: 500;
  line-height: 36px;
}
.home-bottom {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: center;
  padding-top: var(--dl-space-space-threeunits);
  border-color: #222223;
  border-style: dashed;
  flex-direction: column;
  justify-content: center;
  border-top-width: 1px;
}
.home-copyright {
  color: rgba(0, 0, 0, 0.3);
  width: 100%;
  font-size: 12px;
  font-style: normal;
  text-align: center;
  font-weight: 500;
  line-height: 18px;
}
@media(max-width: 991px) {
  .home-main {
    gap: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-threeunits);
  }
  .home-navbar-interactive {
    gap: 0;
    justify-content: space-between;
  }
  .home-links {
    display: none;
  }
  .home-burger-menu {
    display: flex;
  }
  .home-heading {
    font-size: 36px;
    line-height: 46px;
  }
  .home-caption {
    font-size: 16px;
    line-height: 24px;
  }
  .home-buttons {
    flex-direction: column;
  }
  .home-details {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-category {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-category1 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-category2 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-mission {
    gap: var(--dl-space-space-twounits);
  }
  .home-content2 {
    gap: var(--dl-space-space-fourunits);
    align-items: flex-start;
    padding-top: var(--dl-space-space-sixunits);
    flex-direction: column;
    padding-bottom: var(--dl-space-space-sixunits);
    justify-content: flex-start;
  }
  .home-button1 {
    width: 100%;
  }
  .home-quote-one {
    padding-top: var(--dl-space-space-sixunits);
    padding-bottom: var(--dl-space-space-sixunits);
  }
  .home-footer {
    width: 100%;
    padding-top: var(--dl-space-space-sixunits);
  }
}
@media(max-width: 767px) {
  .home-main {
    gap: var(--dl-space-space-threeunits);
    height: 800px;
    position: relative;
    padding-left: 0px;
    flex-direction: column;
  }
  .home-content {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-navbar-interactive {
    gap: 0;
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
    justify-content: space-between;
  }
  .home-desktop-menu {
    display: none;
  }
  .home-burger-menu {
    display: flex;
  }
  .home-image {
    width: 100%;
    padding-top: 0px;
    padding-left: 0px;
    padding-right: 0px;
    background-position: center;
  }
  .home-details {
    gap: var(--dl-space-space-twounits);
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    flex-direction: column;
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-category {
    gap: var(--dl-space-space-unit);
    flex-direction: column;
  }
  .home-category1 {
    gap: var(--dl-space-space-unit);
    flex-direction: column;
  }
  .home-category2 {
    gap: var(--dl-space-space-unit);
    flex-direction: column;
  }
  .home-mission {
    gap: var(--dl-space-space-threeunits);
    padding-top: var(--dl-space-space-sixunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    flex-direction: column;
  }
  .home-content1 {
    max-width: 100%;
  }
  .home-images {
    width: 100%;
    align-items: flex-start;
    flex-direction: column;
    justify-content: flex-start;
  }
  .home-row {
    width: 100%;
    padding-top: var(--dl-space-space-oneandhalfunits);
    justify-content: flex-end;
  }
  .home-image2 {
    bottom: var(--dl-space-space-halfunit);
    position: static;
  }
  .home-content2 {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-quote-content {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-footer {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
}
@media(max-width: 479px) {
  .home-content {
    gap: var(--dl-space-space-threeunits);
  }
  .home-navbar-interactive {
    padding: var(--dl-space-space-unit);
  }
  .home-mobile-menu {
    padding: 16px;
  }
  .home-mission {
    padding-top: var(--dl-space-space-threeunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-title {
    font-size: 12px;
  }
  .home-header1 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-heading1 {
    font-size: 30px;
    line-height: 40px;
  }
  .home-highlights {
    gap: var(--dl-space-space-unit);
    flex-direction: column;
  }
  .home-highlight {
    gap: var(--dl-space-space-unit);
  }
  .home-title1 {
    font-size: 30px;
    line-height: 40px;
  }
  .home-highlight1 {
    gap: var(--dl-space-space-unit);
  }
  .home-title2 {
    font-size: 30px;
    line-height: 40px;
  }
  .home-image1 {
    width: 200px;
  }
  .home-image2 {
    width: 200px;
  }
  .home-content2 {
    padding-top: var(--dl-space-space-threeunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-heading2 {
    font-size: 30px;
    line-height: 40px;
  }
  .home-quote-one {
    padding-top: var(--dl-space-space-threeunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-quote-content {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-quote {
    font-size: 18px;
    text-align: center;
    line-height: 27px;
  }
  .home-quoted {
    flex-direction: column;
    justify-content: center;
  }
  .home-caption1 {
    font-size: 16px;
    font-style: normal;
    font-weight: 500;
  }
  .home-footer {
    padding-top: var(--dl-space-space-threeunits);
  }
  .home-navigation-links {
    flex-direction: column;
  }
  .home-text {
    font-size: 18px;
    line-height: 40px;
  }
  .home-text1 {
    font-size: 18px;
    line-height: 40px;
  }
  .home-bottom {
    padding-top: var(--dl-space-space-oneandhalfunits);
  }
  .home-copyright {
    font-size: 10px;
    line-height: 15px;
  }
}
</style>
