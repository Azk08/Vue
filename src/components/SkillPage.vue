<template>
  <div class="skill">
    <div className="card">
      <img src="../assets/image.png" alt="" />
      <p className="">Front End Programmer</p>
    </div>
    <div className="card">
      <img src="../assets/sass.svg" alt="" />
      <p className="">I can use Css Framework</p>
    </div>
    <div className="card">
      <img src="../assets/design.png" alt="" />
      <p className="">I can use design app</p>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.card {
  display: flex;
  flex-wrap: wrap;
  padding: 10px;
  box-shadow: 5px;
  width: 30%;
  align-items: center;
  justify-content: space-between;
  border-radius: 10px;
  box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.1);
}
.card img{
    width: 30%;
}
.card p{
    width: 50%;
}
</style>
