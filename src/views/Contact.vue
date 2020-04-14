<template>
  <v-container>
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
  </v-container>
</template>

<style scoped>
.myRow {
  margin-top: 30px;
}
</style>

<script>
export default {}
</script>
