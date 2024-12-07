<template>
  <header class="flex items-center space-x-8 mb-8">
    <div class="flex-shrink-0 w-30 h-30">
      <img
        src="@/assets/personal.jpg"
        alt="Personal photo, sorry if it isn't here"
        class="w-full h-full object-cover rounded-full border-4 border-white shadow-md"
      />
    </div>
    <div class="flex-grow">
      <h1 class="text-3xl font-bold tracking-wide text-gray-900 mb-2">
        OLEKSANDR VANIN
      </h1>
      <p class="uppercase tracking-widest text-cutty-sark-500 mb-2">
        PHP Backend / Fullstack Developer
      </p>
      <div class="grid grid-cols-2 gap-x-2 text-sm">
        <div class="flex items-center space-x-2">
          <PhoneIcon class="w-4 h-4 text-cutty-sark-500" />
          <a
            href="tel:+380997421847"
            class="text-cutty-sark-500 hover:underline"
          >
            +380997421847
          </a>
        </div>
        <div class="flex items-center space-x-2">
          <MailIcon class="w-4 h-4 text-cutty-sark-500" />
          <a
            href="mailto:av.chezz@gmail.com"
            class="text-cutty-sark-500 hover:underline"
          >
            av.chezz@gmail.com
          </a>
        </div>
        <div class="flex items-center space-x-2">
          <LinkedinIcon class="w-4 h-4 text-cutty-sark-500" />
          <a
            href="https://www.linkedin.com/in/oleksandr-vanin-2a3b56224/"
            target="_blank"
            class="text-cutty-sark-500 hover:underline"
          >
            oleksandr-vanin-2a3b56224
          </a>
        </div>
        <div class="flex items-center space-x-2">
          <GithubIcon class="w-4 h-4 text-cutty-sark-500" />
          <a
            href="https://github.com/deadbyback"
            target="_blank"
            class="text-cutty-sark-500 hover:underline"
          >
            @deadbyback
          </a>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import {
  Phone as PhoneIcon,
  Mail as MailIcon,
  Linkedin as LinkedinIcon,
  Github as GithubIcon,
} from "lucide-vue-next";

export default {
  name: "Header",
  components: {
    PhoneIcon,
    MailIcon,
    LinkedinIcon,
    GithubIcon,
  },
};
</script>
