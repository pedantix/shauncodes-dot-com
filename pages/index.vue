<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="text-xs-center">
        <img src="/v.png" alt="Vuetify.js" class="mb-5" />
      </div>
      <v-card>
        <v-card-title class="headline">Welcome to Shauncodes.com</v-card-title>
        <v-card-text>
          <p>Hi! My name is Shaun and I code. The name me be a little on the nose but I believe in being simple and straight forward.</p>
          <p>Thank you for visiting my website, pardon the dust I will be working on flesghing out this site with the following features.</p>
          <h3> TODOS! (Pardon my dusst)</h3>
          <ul>
            <li>C. V. - My relevent CV will be posted</li>
            <li>Sharable Work - Most of the work I have done is not shareable, but the work I have done that clients will grant me persmission to include will be presented.</li>
            <li>Blog - A technical and life blog that is to come down the pipeline.</li>
            <li>Open Source Work - I have contributed to the open source community quite a bit and it is time to put it on display.</li>
            <li>Work Inquiry Form - Ask me about what "it"(whatever your it may be) would take! I would love to give a pitch</li>
            <li>Social Media - Akward Nerds should get more Social.</li>
          </ul>
          <div class="text-xs-right">
            <em><small>&mdash; Shaun W. Hubbard</small></em>
          </div>
        </v-card-text>
        <v-card-actions>
          <v-spacer></v-spacer>
          <v-btn color="primary" flat nuxt to="/inspire">Inspire!</v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>
