<template>
  <div>
    <TheNavigation />
    <div class="body">
      <TheBody/>
    </div>
    
    <TheFooter/>
  </div>
</template>

<style scoped>
.footer{
  position: absolute;
  bottom: 0; left: 0; right: 0;
  padding: 0 20px;
  height: 40px;
  background: darkblue;
  color: #fff;
  display: flex;
  align-items: center;
}
.body{
  padding: 60px 2rem;
  max-width: 1240px;
  margin: auto;
  background: ghostwhite;
  height: 100vh;
}
</style>