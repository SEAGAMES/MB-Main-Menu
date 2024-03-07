<template>
  <v-row align="center" justify="center" class="mt-3">
    <!-- Loop through the array and create v-col for each element -->
    <v-col cols="auto">
      <v-card
        class="mx-auto"
        width="200"
        a
        href="https://mb.mahidol.ac.th/mb_certificate/#/"
      >
        <v-img
          src="../assets/menu-img/certificate_menu.png"
          width="140"
          alt="Icon"
          class="mx-auto"
        ></v-img>
        <v-card-actions class="d-flex justify-content-center">
          <v-btn color="orange"> Certificate </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>

    <v-col cols="auto">
      <v-card
        class="mx-auto"
        width="200"
        a
        href="http://10.62.123.151:3200/mb_lab/#/mb-lab"
      >
        <v-img
          src="../assets/menu-img/lab_menu.png"
          width="140"
          alt="Icon"
          class="mx-auto"
        ></v-img>
        <v-card-actions class="d-flex justify-content-center">
          <v-btn color="orange">Request Lab </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
</script>
