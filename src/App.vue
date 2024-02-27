<script setup>
</script>

<template>
  <div class="container">
    <div>
      <img src="/public/dima.jpg"/>
    </div>
    <iframe frameborder="0" style="border:none;width:100%;height:210px;" width="500px" height="210" src="https://music.yandex.ru/iframe/track/16523469/5408809">Слушайте <a href='https://music.yandex.ru/album/5408809/track/16523469'>Habits (Stay High)</a> — <a href='https://music.yandex.ru/artist/1080505'>Tove Lo</a> на Яндекс Музыке</iframe>

  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

img {
  max-width: 300px;
}
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  border-radius: 14px;
  max-width: 300px;
  height: fit-content;
  overflow: hidden;
}
</style>
