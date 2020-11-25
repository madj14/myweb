<template>
  <main>
    <home/>
    <work/>
  </main>
</template>

<script>
import home from '@/components/Home.vue'
import work from  '@/components/Work.vue'
export default {
  name: 'App',
  components: {
    home,
    work
  },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Roboto+Mono&display=swap');
main{
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  position: relative;
}
body{
  margin: 0px;
  font-family: 'Roboto Mono';
}
h1{
  margin: 0;
}
section{
  position: relative;
}
.hover{
  transition: 1s;
}
.hover:hover{
  background-color: #222831;
  transition: 1s;
  color: #eeeeee;
}
.myimg{
  position: absolute;
  bottom: 0;
  right: 0;
  width: 50%;
  overflow: hidden;
  z-index: -1;
}
.myimg img{
  width: 100%;
  vertical-align: middle;
}
.container {
    max-width: 1200px;
    margin: 0 auto;
    position: relative;
}
</style>