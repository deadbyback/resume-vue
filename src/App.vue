<template>
  <div
    class="max-w-4xl mx-auto bg-white p-8 my-12 shadow-lg rounded-lg relative font-sans"
  >
    <Header />
    <Contacts />
    <Profile />
    <Skills />
    <Experience />
    <Education />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Contacts from "./components/Contacts.vue";
import Profile from "./components/Profile.vue";
import Skills from "./components/Skills.vue";
import Experience from "./components/Experience.vue";
import Education from "./components/Education.vue";

export default {
  name: "App",
  components: {
    Header,
    Contacts,
    Profile,
    Skills,
    Experience,
    Education,
  },
};
</script>
