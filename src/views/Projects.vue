<template>
  <v-container text-center>
    <div>
      <h1>Web developer Portfolio</h1>
      <p>I develop applications with Python, Javascript</p>
      <p>Please check my latest portfolio projects</p>
    </div>

    <v-row wrap align="center" justify="center">
      <v-col v-for="(project, index) in projects" :key="index" cols="12" md="4">
        <v-card class="mx-auto" max-width="344">
          <v-card-text>
            <div>{{ project.stack }}</div>
            <p class="display-1 text--primary">
              {{ project.name }}
            </p>

            <div class="text--primary">
              {{ project.Description }}
            </div>
          </v-card-text>

          <v-btn text :href="project.link" color="deep-purple accent-4">
            Let's Go</v-btn
          >
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data () {
    return {
      projects: [
        {
          name: 'Ecommerce',
          stack: 'Python, Javascript',
          link: 'https://github.com/ashish-bisht/ecommerce',
          Description: 'asdf gdogj sfsdfsd dgfhd'
        },
        {
          name: 'Ecommerce',
          stack: 'Python, Javascript',
          link: 'https://github.com/ashish-bisht/ecommerce',
          Description: 'asdf gdogj sfsdfsd dgfhd'
        },
        {
          name: 'Ecommerce',
          stack: 'Python, Javascript',
          link: 'https://github.com/ashish-bisht/ecommerce',
          Description: 'asdf gdogj sfsdfsd dgfhd'
        },
        {
          name: 'Ecommerce',
          stack: 'Python, Javascript',
          link: 'https://github.com/ashish-bisht/ecommerce',
          Description: 'asdf gdogj sfsdfsd dgfhd'
        },
        {
          name: 'Ecommerce',
          stack: 'Python, Javascript',
          link: 'https://github.com/ashish-bisht/ecommerce',
          Description: 'asdf gdogj sfsdfsd dgfhd'
        },
        {
          name: 'Ecommerce',
          stack: 'Python, Javascript',
          link: 'https://github.com/ashish-bisht/ecommerce',
          Description: 'asdf gdogj sfsdfsd dgfhd'
        },
        {
          name: 'Ecommerce',
          stack: 'Python, Javascript',
          link: 'https://github.com/ashish-bisht/ecommerce',
          Description: 'asdf gdogj sfsdfsd dgfhd'
        }
      ]
    }
  }
}
</script>
