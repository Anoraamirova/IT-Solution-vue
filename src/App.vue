<template>
  <div id="app">
    <Header />
    <Banner />
    <WeTxt />
    <WeOffer />
    <OurWorks />
    <OurTeam />
    <OurPartners />
    <LatestNews />
    <CallUs />
    <Contacts />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Banner from "./components/Banner.vue";
import WeTxt from "./components/WeTxt.vue";
import WeOffer from "./components/WeOffer.vue";
import OurWorks from "./components/OurWorks.vue";
import OurTeam from "./components/OurTeam.vue";
import OurPartners from "./components/OurTeam.vue";
import LatestNews from "./components/LatestNews.vue";
import Contacts from "./components/Contacts.vue";
import CallUs from "./components/CallUs.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Banner,
    WeTxt,
    WeOffer,
    OurWorks,
    OurTeam,
    OurPartners,
    LatestNews,
    Contacts,
    CallUs,
    Footer,
  },
};
</script>

<style>
#app {
  font-size: 20px;
  text-align: center;
  color: var(--thm-text);
  line-height: 1.8em;
  font-weight: 300;
  background: #ffffff;
  -webkit-font-smoothing: antialiased;
  -moz-font-smoothing: antialiased;
  font-family: var(--thm-font);
  top: 0 !important;
}
</style>
