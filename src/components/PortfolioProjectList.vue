<template>
  <!-- project list -->
  <div class="project">
    <div class="project__title">My Projects</div>
    <div class="project__list">
      <a href="https://ecommerce-cabi-1cd08.web.app/home" class="project__item">
        <img src="../assets/img/cabi.jpg" alt="" class="project__img" />
        <h2 class="project__name">Cabi</h2>
      </a>

      <a href="https://minh0127.github.io/BucketList/#" class="project__item">
        <img src="../assets/img/bucket.jpg" alt="" class="project__img" />
        <h2 class="project__name">Bucket List</h2>
      </a>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.project__title {
  text-align: center;
  font-size: 60px;
}

.project__list {
  display: flex;
  gap: 40px;
  margin-block: 60px;
}

.project__item {
  max-width: 50%;
  position: relative;
}

.project__img {
  max-width: 100%;
  border-radius: 16px;
  border: 5px solid transparent;
  filter: grayscale(1);
  transition: all 0.25s linear;
}

.project__item:hover .project__img {
  border: 5px solid #002eff;
  filter: grayscale(0);
}

.project__item:hover .project__name {
  opacity: 0;
}

.project__name {
  position: absolute;
  color: #002eff;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-shadow: 2px 2px 2px black;
  font-size: 40px;
  transition: all 0.25s linear;
}
</style>
