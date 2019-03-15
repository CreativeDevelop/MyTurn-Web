<template>
  <div id="teste">
      <h1>TESTE</h1>
    <p>{{ $t('hello') }}</p>
    <p>{{$t('play')}}</p>
  </div>
</template>

<script>
export default {
  name: 'HelloI18n'
}
</script>

<i18n>
{
  "en": {
    "hello": "Hello i18n in SFC!"
  },
  "pt-br": {
    "hello": "Olá caros amigos!"
  }
}
</i18n>

<style scoped>
#teste {
    margin-top: 100px;
    margin-left: 100px;
}
</style>
