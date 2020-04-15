<template>
  <v-container>
    <v-row>
      <v-col md="8" col="4">
        <h2 class="htmlTag">
          <i> &lt;html &gt;</i>
        </h2>
        <h2 class="bodyTag">
          <i>&lt;body &gt;</i>
        </h2>

        <h2 class="h1Tag">
          <i>&lt;h1 &gt;</i>
        </h2>

        <div class="mainText">
          <h1>Hello,</h1>
          <h1 class="font-weight-white">I'm Ashish Bisht,</h1>
          <h1>
            Full Stack Developer.
            <i>&lt;h1&gt;</i>
          </h1>
          <p>Python | Javascript</p>
          <v-btn outlined to="/contact">
            Contact Me
          </v-btn>
        </div>
        <br />
        <br />
        <h2 class="bodyTag">
          <i>&lt;/body &gt;</i>
        </h2>
        <h2 class="htmlTag">
          <i>&lt;/html &gt;</i>
        </h2>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.htmlTag {
  padding-left: 0px;
}

.bodyTag {
  padding-left: 10px;
}

.h1Tag {
  padding-left: 15px;
}

h2 {
  color: navy;
  padding-bottom: 30px;
}

i {
  /* font-family: La Belle Aurore, cursive; */
  font-size: 1rem;
  color: navy;
}

.mainText {
  padding-left: 30px;
  font-size: 1.7rem;

  /* text-shadow: 2px 2px 5px grey; */
}

@media (max-width: 640px) {
  .mainText {
    font-size: 0.9rem;
  }
  i {
    font-family: La Belle Aurore, cursive;
    font-size: 0.7rem;
    color: navy;
  }
  h2 {
    color: navy;
    padding-bottom: px;
  }
}
</style>

<script>
export default {
  name: 'Home',
  components: {
    // HelloWorld
  },

  data () {
    return {
      techs: ['Python', 'Javascript', 'Django', 'Vue', 'AWS', 'Linux', 'OSX']
    }
  }
}
</script>
