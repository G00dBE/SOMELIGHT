<template>
  <div id="mystory">
    <div id="mystorytitle">내가 쓴 사연</div>
    <my-story-list-comp />
  </div>
</template>

<script>
import MyStoryListComp from './MyStoryListComp.vue'

export default {
  components: { MyStoryListComp },

}
</script>

<style scoped>
#mystory{
  font-family: "Dovemayo_gothic";
  width: 40vw;
  height: 70vh;
  border-radius: 20px;
  color:#4D455D;
  background-color: linear-gradient(
    rgb(158, 158, 158,0.2), 
    rgba(250,250,250,0.9)) #F5E9CF;
  opacity: 0.85;
  display: flex;
  justify-content: center;
  flex-direction: column;
  box-shadow: 2px 2px 2px rgb(216, 216, 216);
}
#mystorytitle{
  margin-top:1%;
  padding-top:1%;
  font-size:3rem;
  font-weight: bold;
  color: #4D455D;
  text-align: center;
}


</style>