<template>
  <app-header />

  <router-view v-slot="{ Component }">
    <transition name="fade" mode="out-in">
      <component :is="Component"></component>
    </transition>
  </router-view>

  <app-player />

  <auth />
</template>

<script>
import { mapWritableState } from 'pinia'
import AppHeader from '@/components/Header.vue'
import Auth from '@/components/Auth.vue'
import AppPlayer from '@/components/Player.vue'
import useUserStore from '@/stores/user'
import { auth } from '@/includes/firebase'
import { RouterView } from 'vue-router'

export default {
  name: 'App',
  components: {
    AppHeader,
    Auth,
    AppPlayer,
    RouterView
  },
  computed: {
    ...mapWritableState(useUserStore, ['userLoggedIn'])
  },
  created() {
    if (auth.currentUser) {
      this.userLoggedIn = true
    }
  }
}
</script>

<style>
.fade-enter-from {
  opacity: 0;
}

.fade-enter-active {
  transition: all 0.5s linear;
}

.fade-leave-to {
  transition: all 0.5s linear;
  opacity: 0;
}
</style>
