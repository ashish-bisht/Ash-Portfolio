<template>
  <v-container justify="center" align="center">
    <v-row>
      <v-col>
        <div class="contactHolder">
          <v-row justify="center" align="center" class="myRow">
            <v-col col="12" md="4">
              <v-card>
                <v-list-item>
                  <v-list-item-avatar color="black"></v-list-item-avatar>
                  <v-list-item-content>
                    <v-list-item-title class="headline"
                      >Mobile</v-list-item-title
                    >
                    <v-list-item-subtitle>Ashish</v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>

                <v-img src="@/assets/phone.jpg"></v-img>

                <v-card-text>
                  <v-btn text><v-icon>mdi-phone</v-icon></v-btn>
                  <b>+91 8618126498</b> <b>+91 8277330427</b>
                </v-card-text>
              </v-card>
            </v-col>

            <v-col col="12" md="4">
              <v-card>
                <v-list-item>
                  <v-list-item-avatar color="black"></v-list-item-avatar>
                  <v-list-item-content>
                    <v-list-item-title class="headline"
                      >Address</v-list-item-title
                    >
                    <v-list-item-subtitle>Ashish</v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>

                <v-img src="@/assets/address.jpg"></v-img>

                <v-card-text>
                  <v-btn text><v-icon>mdi-home</v-icon></v-btn>
                  <b>Bangalore , India</b>
                </v-card-text>
              </v-card>
            </v-col>

            <v-col col="12" md="4">
              <v-card>
                <v-list-item>
                  <v-list-item-avatar color="black"></v-list-item-avatar>
                  <v-list-item-content>
                    <v-list-item-title class="headline"
                      >Email</v-list-item-title
                    >
                    <v-list-item-subtitle>Ashish</v-list-item-subtitle>
                  </v-list-item-content>
                </v-list-item>

                <v-img src="@/assets/email.jpg"></v-img>

                <v-card-text>
                  <v-btn text class="ml-20"><v-icon>mdi-email</v-icon></v-btn>
                  <b>ashishbisht723@gmail.com</b>
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </div>
      </v-col>
    </v-row>
    <v-divider></v-divider>
    <v-divider></v-divider>

    <v-row align="center" justify="center">
      <v-col>
        <transition name="fade">
          <div>
            <v-card
              align="center"
              justify="center"
              class="mx-auto"
              dark
              max-width="400"
            >
              <v-card-title>
                <v-btn text href="https://github.com/ashish-bisht/"
                  ><v-icon large>mdi-github</v-icon></v-btn
                >
                <v-spacer></v-spacer>
                <v-btn text href="https://www.linkedin.com/in/ashish-bisht723/"
                  ><v-icon large>mdi-linkedin</v-icon></v-btn
                >
              </v-card-title>

              <!-- <v-card-text class="headline font-weight-bold">
            My Social Accounts
          </v-card-text> -->
            </v-card>
          </div>
        </transition>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.myRow {
  margin-top: 30px;
}

.fade-enter {
  opacity: 0;
}

.fade-enter-avtive {
  transition: opacity 1s;
}

.fade-leave {
}

.fade-leave-active {
  transition: opacity 1s;
  opacity: 0;
}
</style>

<script>
export default {}
</script>
