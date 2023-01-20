<template>
  <div id="banner" data-persistence="true" class="banner-banner">
    <div class="banner-captions">
      <div class="banner-caption">
        <span class="banner-text">{{ Caption }}</span>
        <a
          :href="Redirect"
          target="_blank"
          rel="noreferrer noopener"
          class="banner-link"
        >
          {{ Bold }}
        </a>
      </div>
      <a :href="RedirectMobile" class="banner-link1">
        <div class="banner-caption1">
          <span class="banner-text1">{{ CaptionMobile }}</span>
          <span class="banner-text2">{{ Bold1 }}</span>
        </div>
      </a>
    </div>
    <div id="close" class="banner-close">
      <svg viewBox="0 0 1024 1024" class="banner-icon">
        <path
          d="M225.835 286.165l225.835 225.835-225.835 225.835c-16.683 16.683-16.683 43.691 0 60.331s43.691 16.683 60.331 0l225.835-225.835 225.835 225.835c16.683 16.683 43.691 16.683 60.331 0s16.683-43.691 0-60.331l-225.835-225.835 225.835-225.835c16.683-16.683 16.683-43.691 0-60.331s-43.691-16.683-60.331 0l-225.835 225.835-225.835-225.835c-16.683-16.683-43.691-16.683-60.331 0s-16.683 43.691 0 60.331z"
        ></path>
      </svg>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Banner',
  props: {
    Bold1: {
      type: String,
      default: 'newsletter',
    },
    Redirect: {
      type: String,
      default: 'https://medium.com',
    },
    Caption: {
      type: String,
      default: 'Get updates and action alerts from Helpa by joining our',
    },
    CaptionMobile: {
      type: String,
      default: 'Join our',
    },
    Bold: {
      type: String,
      default: 'newsletter',
    },
    RedirectMobile: {
      type: String,
      default: 'https://medium.com',
    },
  },
}
</script>

<style scoped>
.banner-banner {
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  padding-top: var(--dl-space-space-oneandhalfunits);
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-oneandhalfunits);
  justify-content: center;
  background-color: #0F1015;
}
.banner-captions {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.banner-caption {
  gap: 4px;
  width: 100%;
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-unit);
  flex-direction: row;
  justify-content: center;
}
.banner-text {
  color: rgb(246, 245, 237);
  font-size: 14px;
  text-align: center;
}
.banner-link {
  color: rgb(246, 245, 237);
  cursor: pointer;
  font-size: 14px;
  font-style: normal;
  text-align: center;
  transition: 0.3s;
  font-weight: 700;
  text-decoration: none;
}
.banner-link:hover {
  color: grey;
}
.banner-link1 {
  display: contents;
}
.banner-caption1 {
  gap: 4px;
  width: 100%;
  display: none;
  align-items: center;
  padding-left: var(--dl-space-space-unit);
  flex-direction: row;
  justify-content: center;
}
.banner-text1 {
  color: rgb(246, 245, 237);
  font-size: 14px;
  text-align: center;
}
.banner-text2 {
  color: rgb(246, 245, 237);
  cursor: pointer;
  font-size: 14px;
  font-style: normal;
  text-align: center;
  transition: 0.3s;
  font-weight: 700;
}
.banner-text2:hover {
  color: grey;
}
.banner-close {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.banner-icon {
  fill: #ffffff;
  width: var(--dl-size-size-xsmall);
  cursor: pointer;
  height: var(--dl-size-size-xsmall);
  transition: 0.3s;
}
.banner-icon:hover {
  fill: grey;
}
@media(max-width: 479px) {
  .banner-caption {
    display: none;
  }
  .banner-caption1 {
    display: flex;
    padding-left: 0px;
  }
  .banner-icon {
    display: none;
  }
}
</style>
