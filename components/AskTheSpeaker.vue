<template>
  <a
    class="button is-dark is-rounded ask-a-question"
    href="https://privacyweek.at/fragen"
    target="_blank"
    rel="noopener"
  >
    {{ $t('currentlyPlaying.askTheSpeaker') }}
  </a>
</template>

<style lang="scss" scoped>
@import '~assets/scss/main.scss';
@import '~bulma/bulma';

a.button.ask-a-question {
  background-color: $color-violet;
  font-weight: bold;
  transition: background-color 0.3s linear;
}
a.button.ask-a-question:hover,
a.button.ask-a-question:active {
  background-color: #622e6f;
}
</style>