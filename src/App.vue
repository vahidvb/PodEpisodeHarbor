<template>
  <div class="main">
    <h1 class="podcast-title">Learn English | EnglishClass101.com</h1>
    <p class="podcast-description">Learn English with Free Podcasts Whether you are student or a seasoned speaker, our lessons offer something for everyone. We incorporate culture and current issues into each episode to give the most informative, both linguistically and culturally, podcasts possible. For those of you with just the plane ride to prepare, check our survival phrase series at EnglishClass101.com. One of these phrases just might turn your trip into the best one ever!</p>
    <h2 class="podcast-title">Listen to EnglishClass101 episodes</h2>
    <Episode v-for="episode in episodes" :episode="episode" :key="episode.Number" />
  </div>
</template>
<script>

import Episode from './components/Episode.vue'
import EpisodesFile from './assets/episodes.json';
export default {
  name: 'App',
  components: {
    Episode
  },
  data() {
    return {
      episodes: EpisodesFile
    };
  }
}
</script>