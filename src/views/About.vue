<template>
  <div class="about">
    <section class="mb-8 py-8 text-center relative mx-2">
      <div class="container mx-auto">
        <div class="text-secondary main-header-content">
          <h1 class="font-bold text-4xl mb-6">{{ $t('about.header') }}</h1>
          <p class="w-full max-w-3xl mx-auto text-left">
            <strong
              ><i>{{ $t('about.mission_title') }}</i></strong
            >: {{ $t('about.mission') }}
            <br />
            <br />
            <strong
              ><i>{{ $t('about.history_title') }}</i></strong
            >: {{ $t('about.history') }}
            <br />
            <br />
            <br />
          </p>
          <div class="container grid align-middle justify-center">
            <img src="/assets/img/compose_music.svg" alt="" />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: 'About'
}
</script>
