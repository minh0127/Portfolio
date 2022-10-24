<template>
  <!-- profile -->
  <div class="profile">
    <div class="profile__about">
      <h2 class="profile__title">About</h2>
      <div class="profile__text">
        Currently, I'm a final-year student of Software Engineering at Hanoi
        University of Industry, a public college based in Hanoi. I expect to
        graduate in June 2023. I have got 3.2/4.0 GPA for now and I hope to keep
        the score until graduation.
      </div>
    </div>

    <div class="profile__skills">
      <h2 class="profile__title">Skills</h2>
      <div class="profile__text">
        I can work well with HTML, CSS, JS, Vue and some Vue-ecosystem like
        Vuex, Vue-router, etc. Besides, I've joined a internship at MISA JSC
        that help me approach to other programming languages and other
        technologies. And moreover, I took part in the real working environment.
      </div>
    </div>

    <div class="profile__experience">
      <h2 class="profile__title">Experience</h2>
      <div class="profile__text">
        I was a web developer intern for MISA JSC for 2 months. During that
        time, my duty was to create a module of a website that allows users to
        manage teacher information by adding, updating, deleting, searching
        information and users can export those data to Excel for sharing. That
        make managing data easier than ever.
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.profile {
}

.profile__about,
.profile__experience {
  width: 45%;
}

.profile__skills {
  width: 45%;
  margin-left: auto;
  text-align: right;
}

.profile__title {
  font-size: 40px;
  text-decoration: underline;
  margin: 20px;
}

.profile__text {
  font-size: 24px;
}
</style>
