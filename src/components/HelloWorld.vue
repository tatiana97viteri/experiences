<template>
  <div>
    <v-flex xs12 class="container">
      <v-img src="https://images.pexels.com/photos/1271619/pexels-photo-1271619.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" alt="home img">
        <v-layout
          align-end
          fill-height
          pa-3
          white--text
        >
          <div class="title font-weight-light">
            <p>Este es un buen día para</p>
            <h1>UNA NUEVA EXPERIENCIA</h1>
            <p>Descubre los mejores lugares a tu alrededor</p>
            <v-btn round color="primary" large>Registrate</v-btn>
          </div>
        </v-layout>
      </v-img>
    </v-flex>    
  </div>
</template>

<script>
  export default {
    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader'
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify'
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify'
        }
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com'
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com'
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuetifyjs.com'
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs'
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify'
        }
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer'
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/layout/pre-defined'
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions'
        }

      ]
    })
  }
</script>

<style>
  .container{
  position: relative;
  padding: 0%;
  }
  img{
    object-fit: cover;
  }
  .title{
    float: left;
    position: absolute;
    /* top: 0%; */
    bottom: 25%;
    /* left: 5%; */
    text-align: left;
    padding: 18% 0 0 10%;
    color: white;
  }
  .title p,h1{
    margin: 5px;
  }
  p{
    font-size: 20px;
  }
  h1{
    font-size: 30px;
  }
</style>
