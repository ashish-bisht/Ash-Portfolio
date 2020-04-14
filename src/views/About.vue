<template>
  <v-container>
    <v-row>
      <v-col md="8">
        <h1>Skills & Experience</h1>
        <p>Mainly my area of expertise is <b>Backend </b> development</p>
        <p>Python is my core language with Django as web framework</p>
        <p>I also code in Javascript with Vue as framework</p>
        <p>I have good intrest on Algorithms and Data strutures</p>
        <p>I do leetcode to get more and more better</p>
      </v-col>

      <v-col class="chip">
        <v-row>
          <v-col
            md="12"
            sm="12"
            xs="12"
            align="center"
            justify="center"
            v-for="(tech, index) in techs"
            :key="index"
          >
            <v-chip class="ma-2" color="indigo" text-color="white">
              {{ tech }}
            </v-chip>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
h1 {
  padding-top: 50px;
  font-size: 3rem;
  padding-bottom: 20px;
}

.chip {
  padding-top: 50px;
}

p {
  font-size: 1.1rem;
}

b {
  color: blue;
  font-size: 1.3rem;
}
</style>

<script>
export default {
  data () {
    return {
      techs: [
        'Python',
        'Javascript',
        'Django',
        'Vue',
        'Algorithms',
        'Data structures'
      ]
    }
  }
}
</script>
