<script setup>
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
    <template #heading>Tentang Saya</template>

    <a href="https://vuejs.org/" target="_blank" rel="noopener"></a>
    Saya Zulfiana Jumadilla Lubis. Saya mahasiswi Teknik Informatika di Universitas Islam Riau. Saya
    lahir di Pekanbaru pada tanngal 16 Juli 2004. Saat ini saya tengah memasuki semester 4 pada
    perkuliahan.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>
    <h3>- SDN 39 Pekanbaru</h3>
    <h3>- SMPN 9 Pekanbaru</h3>
    <h3>- SMAN 10 Pekanbaru</h3>
    <h3>- Universitas Islam Riau</h3>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Hobi</template>
    <h3>- Menonton</h3>
    <h3>- Mendengarkan musik</h3>
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://router.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://test-utils.vuejs.org/" target="_blank" rel="noopener"></a>
    <a href="https://github.com/vuejs/devtools" target="_blank" rel="noopener"></a>

    <a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Social Media</template>

    Instagram: @zlfnjmdilla
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://stackoverflow.com/questions/tagged/vue.js" target="_blank" rel="noopener"></a>
    <a href="https://news.vuejs.org" target="_blank" rel="noopener"></a>
    <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"></a>
  </WelcomeItem>

  <template>
    <SupportIcon />
  </template>
  <template></template>
</template>
