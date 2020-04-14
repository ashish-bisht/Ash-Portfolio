<template>
  <v-container>
    <v-navigation-drawer
      v-model="drawer"
      :color="color"
      :expand-on-hover="expandOnHover"
      :mini-variant="miniVariant"
      :left="left"
      absolute
      dark
    >
      <v-row justify="center" align="center">
        <v-col>
          <v-list dense nav class="py-0">
            <v-list-item two-line :class="miniVariant && 'px-0'">
              <v-list-item-avatar>
                <img src="@/assets/ace.jpg" />
              </v-list-item-avatar>
            </v-list-item>
          </v-list>
        </v-col>
        <v-col>
          <v-list-item v-for="item in items" :key="item.title" link>
            <v-list-item-icon>
              <v-icon>{{ item.icon }}</v-icon>
            </v-list-item-icon>

            <v-list-item-content>
              <v-list-item-title>{{ item.title }}</v-list-item-title>
            </v-list-item-content>
          </v-list-item>
        </v-col>
      </v-row>
    </v-navigation-drawer>
  </v-container>
</template>

<script>
export default {
  data () {
    return {
      drawer: true,
      items: [
        { title: 'Dashboard', icon: 'mdi-view-dashboard' },
        { title: 'Photos', icon: 'mdi-image' },
        { title: 'About', icon: 'mdi-help-box' }
      ],
      color: 'black',
      colors: ['primary', 'blue', 'success', 'red', 'teal'],
      left: true,
      miniVariant: true,
      expandOnHover: true,
      background: false
    }
  }
}
</script>
