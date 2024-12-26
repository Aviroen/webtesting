<template>
  <div class="home-container1">
    <app-banner1>
      <template v-slot:content1>
        <div class="home-fragment1">
          <span class="home-text1">Some dumb egg on the internet</span>
        </div>
      </template>
      <template v-slot:heading1>
        <div class="home-fragment2">
          <span class="home-text2">Aviroen&apos;s Little Hovel</span>
        </div>
      </template>
    </app-banner1>
    <div class="home-container2">
      <a
        href="https://voidsent-sdv.fandom.com/wiki/Voidsent_Wiki"
        target="_blank"
        rel="noreferrer noopener"
        class="home-link1"
      >
        Voidsent
      </a>
      <a
        href="https://ko-fi.com/aviroen"
        target="_blank"
        rel="noreferrer noopener"
        class="home-link2"
      >
        Kofi
      </a>
      <a
        href="https://www.patreon.com/c/aviroen"
        target="_blank"
        rel="noreferrer noopener"
        class="home-link3"
      >
        Patreon
      </a>
      <a
        href="https://next.nexusmods.com/profile/aviroen"
        target="_blank"
        rel="noreferrer noopener"
        class="home-link4"
      >
        Nexus
      </a>
    </div>
    <div class="home-container3">
      <a
        href="https://github.com/Aviroen"
        target="_blank"
        rel="noreferrer noopener"
        class="home-link5"
      >
        <svg width="32" height="32" viewBox="0 0 32 32" class="home-icon1">
          <path
            d="M16 2a14 14 0 0 0-4.43 27.28c.7.13 1-.3 1-.67v-2.38c-3.89.84-4.71-1.88-4.71-1.88a3.7 3.7 0 0 0-1.62-2.05c-1.27-.86.1-.85.1-.85a2.94 2.94 0 0 1 2.14 1.45a3 3 0 0 0 4.08 1.16a2.93 2.93 0 0 1 .88-1.87c-3.1-.36-6.37-1.56-6.37-6.92a5.4 5.4 0 0 1 1.44-3.76a5 5 0 0 1 .14-3.7s1.17-.38 3.85 1.43a13.3 13.3 0 0 1 7 0c2.67-1.81 3.84-1.43 3.84-1.43a5 5 0 0 1 .14 3.7a5.4 5.4 0 0 1 1.44 3.76c0 5.38-3.27 6.56-6.39 6.91a3.33 3.33 0 0 1 .95 2.59v3.84c0 .46.25.81 1 .67A14 14 0 0 0 16 2"
            fill="currentColor"
            fill-rule="evenodd"
          ></path>
        </svg>
      </a>
      <a
        href="https://discord.gg/JnWpXrRt9Y"
        target="_blank"
        rel="noreferrer noopener"
        class="home-link6"
      >
        <svg width="32" height="32" viewBox="0 0 32 32" class="home-icon3">
          <path
            d="M25.7 7.1Q23 5.9 20 5.3h-.1c-.2.4-.5 1-.7 1.5c-2.2-.3-4.3-.3-6.4 0c-.2-.5-.5-1-.7-1.5H12q-3 .45-5.7 1.8C2.7 12.5 1.7 17.8 2.2 23v.1c2.4 1.8 4.7 2.8 7 3.5h.1c.5-.7 1-1.5 1.4-2.3v-.1c-.8-.3-1.5-.6-2.2-1c-.1 0-.1-.1 0-.1c.1-.1.3-.2.4-.3H9c4.6 2.1 9.5 2.1 14.1 0h.1c.1.1.3.2.4.3c.1 0 0 .1 0 .1c-.7.4-1.4.8-2.2 1c0 0-.1.1 0 .1c.4.8.9 1.6 1.4 2.3h.1c2.3-.7 4.6-1.8 7-3.5V23c.6-6-1-11.2-4.2-15.9M11.4 19.9c-1.4 0-2.5-1.3-2.5-2.8s1.1-2.8 2.5-2.8s2.5 1.3 2.5 2.8s-1.1 2.8-2.5 2.8m9.3 0c-1.4 0-2.5-1.3-2.5-2.8s1.1-2.8 2.5-2.8s2.5 1.3 2.5 2.8s-1.1 2.8-2.5 2.8"
            fill="currentColor"
          ></path>
        </svg>
      </a>
    </div>
    <img
      alt="image"
      src="https://i.imgur.com/bQgJXzO.png"
      loading="lazy"
      class="home-image"
    />
  </div>
</template>

<script>
import AppBanner1 from '../components/banner1'

export default {
  name: 'Home',
  props: {},
  components: {
    AppBanner1,
  },
  metaInfo: {
    title: 'Pleasing Partial Worm',
    meta: [
      {
        property: 'og:title',
        content: 'Pleasing Partial Worm',
      },
    ],
  },
}
</script>

<style scoped>
.home-container1 {
  width: 100%;
  display: flex;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
 
.home-fragment1 {
  display: contents;
}
 
.home-text1 {
  display: inline-block;
}
 
.home-fragment2 {
  display: contents;
}
 
.home-text2 {
  display: inline-block;
}
 
.home-container2 {
  gap: var(--dl-space-space-oneandhalfunits);
  flex: 0 0 auto;
  width: auto;
  height: auto;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-unit);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-unit);
  justify-content: center;
}
 
.home-link1 {
  font-size: 36px;
  align-self: center;
  text-align: center;
  text-decoration: none;
}
 
.home-link2 {
  font-size: 36px;
  align-self: center;
  text-align: center;
  text-decoration: none;
}
 
.home-link3 {
  font-size: 36px;
  align-self: center;
  text-align: center;
  text-decoration: none;
}
 
.home-link4 {
  font-size: 36px;
  align-self: center;
  text-align: center;
  text-decoration: none;
}
 
.home-container3 {
  flex: 0 0 auto;
  width: auto;
  height: 81px;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
 
.home-link5 {
  display: contents;
}
 
.home-icon1 {
  width: 122px;
  height: 81px;
  text-decoration: none;
}
 
.home-link6 {
  display: contents;
}
 
.home-icon3 {
  width: 175px;
  height: 77px;
  text-decoration: none;
}
 
.home-image {
  width: 200px;
  object-fit: cover;
}
</style>
