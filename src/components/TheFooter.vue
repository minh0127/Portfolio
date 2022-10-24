<template>
  <!-- footer -->
  <div class="footer">
    <div class="footer__contact">
      <h2 class="contact__text">Contact me</h2>
      <div>+8433 310 6201</div>
      <div>buithanhminh.work@gmail.com</div>
      <div class="contact__btn">
        <a href="mailto:buithanhminh.work@gmail.com" class="contact__link"
          >Email me</a
        >
      </div>
    </div>
    <div class="footer__credit">
      <div>© Minh Bui. All rights reserved</div>
      <div>Thanks for being here!</div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.footer__contact {
  display: flex;
  flex-direction: column;
  gap: 20px;
  align-items: center;
  border-bottom: 5px solid #fff;
  padding-bottom: 40px;
}

.contact__text {
  font-size: 40px;
}

.contact__btn {
  background: #fff;
  width: 250px;
  height: 50px;
  transform: translateY(10px);
  transition: all 0.25s ease-out;
}

.contact__btn:hover {
  transform: translateY(0);
}

.contact__link {
  font-size: 24px;
  color: #002eff;
  line-height: 50px;
  text-align: center;
  display: block;
  font-weight: 700;
}

.footer__credit {
  display: flex;
  justify-content: space-between;
  padding-block: 30px;
}
</style>
