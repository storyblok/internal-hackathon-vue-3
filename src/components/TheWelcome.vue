<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Resources</template>

    Vue’s
    <a href="https://vuejs.org/" target="_blank" rel="noopener">official documentation</a>
    provides you with all information you need to get started. Specifically the 
    <a href="hhttps://vuejs.org/guide/extras/composition-api-faq.html" target="_blank" rel="noopener noreferrer">Composition API</a> guide, as well as the <a href="https://vuejs.org/examples/#todomvc" target="_blank" rel="noopener noreferrer">examples</a> are a great starting point to learn. You can also check out <a href="https://vueschool.io/" target="_blank" rel="noopener noreferrer">Vue School</a> and <a href="https://vuedose.tips/articles" target="_blank" rel="noopener noreferrer">Vue Dose</a> aswell as <a href="https://next.awesome-vue.js.org/" target="_blank" rel="noopener noreferrer">Awesome Vue</a> for more resources.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Videos</template>

    You can watch <a href="https://www.youtube.com/watch?v=ZqgiuPt5QZo" target="_blank" rel="noopener"> this video</a> to learn about Vue 3 in general. This video will give you some detailed insight into the  <a href="https://www.youtube.com/watch?v=bwItFdPt-6M" target="_blank" rel="noopener">Composition API</a>. The <a href="https://www.youtube.com/watch?v=WLpLYhnGqPA" target="_blank" rel="noopener noreferrer">Design Principles of Vue 3.0</a> will teach you more about what the whole principle behind the updated framework are. And this is a super fast <a href="https://www.youtube.com/watch?v=nhBVL41-_Cw&t=31s" target="_blank" rel="noopener noreferrer">2-minute video</a> about Vue in general.
   
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Component Library</template>

    We installed <a href="https://element-plus.org/en-US/" target="_blank" rel="noopener noreferrer">Element Plus</a> into this starter template, but there a dozens of other <a href="https://github.com/vuejs/awesome-vue#responsive" target="_blank" rel="noopener noreferrer">component libraries</a> you can try out. You can see Element components on the  <RouterLink to="/example">example page</RouterLink>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Utilities</template>

    For utility libraries we installed <a href="https://vueuse.org/" target="_blank" rel="noopener noreferrer">vueuse</a>, but you can find more vue utility libraries  <a href="https://github.com/vuejs/awesome-vue#utilities" target="_blank" rel="noopener noreferrer">here</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Thanks for taking part!</template>

    We're happy you're joining the hackathon and are looking forward to see what you'll build :) 
  </WelcomeItem>
</template>
