<template>
  <!-- info -->
  <div>
    <div class="info">
      <div class="info__left">
        <h3 class="info__text">Hi! My name is</h3>

        <div class="info__name">
          <span style="--i: 1">M</span>
          <span style="--i: 2">i</span>
          <span style="--i: 3">n</span>
          <span style="--i: 4">h</span>
          <span style="--i: 5">&#160;</span>
          <span style="--i: 6">B</span>
          <span style="--i: 7">u</span>
          <span style="--i: 8">i</span>
        </div>

        <h2 class="info__role">
          I'm a <span style="color: #002eff">Front-end</span> Developer
        </h2>
      </div>

      <div class="info__right">
        <img src="../assets/img/avt.png" alt="avatar" class="info__avatar" />
        <div class="info__contact">
          <div class="contact__text">My social media</div>
          <div class="contact__btn">
            <a href="https://www.facebook.com/minh0127" class="contact__link">
              <div class="facebook link-icon"></div>
            </a>
          </div>
          <div class="contact__btn">
            <a href="https://github.com/minh0127" class="contact__link">
              <div class="github link-icon"></div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.info {
  display: flex;
  justify-content: space-between;
}

.info__text {
  font-weight: 400;
  font-size: 24px;
}

.info__name {
  position: relative;
  -webkit-box-reflect: below -20px linear-gradient(transparent, rgba(0, 0, 0, 0.2));
  font-size: 160px;
}

.info__name span {
  position: relative;
  display: inline-block;
  animation: wave 1s infinite;
  animation-delay: calc(0.1s * var(--i));
  font-weight: 900;
}

.info__role {
  margin-top: 190px;
  font-size: 40px;
}

.info__right {
  display: flex;
  gap: 24px;
  align-items: center;
}

.info__avatar {
  border-radius: 100%;
  border: 5px solid #fff;
  width: 300px;
  height: 350px;
  object-fit: cover;
  object-position: top;
}

.info__contact {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
}

.contact__text {
  writing-mode: tb;
  font-size: 20px;
}

.contact__btn:hover {
  color: red;
}

.link-icon {
  background-size: contain;
  width: 40px;
  height: 40px;
  transition: all 0.25s ease-out;
}

.facebook {
  background-image: url(../assets/img/facebook.png);
}

.facebook:hover {
  background-image: url(../assets/img/facebook_hover.png);
}

.github {
  background-image: url(../assets/img/github.png);
}

.github:hover {
  background-image: url(../assets/img/github_hover.png);
}

@keyframes wave {
  0%,
  40%,
  100% {
    transform: translateY(0);
  }
  20% {
    transform: translateY(-20px);
  }
}
</style>
