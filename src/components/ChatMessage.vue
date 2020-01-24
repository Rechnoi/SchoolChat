<template>
  <div class="chat-message">
    <div class="info">Ivan 21.12.2019 05:00:50</div>
    Hello, World!!!
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',

  data: () => ({
    ecosystem: [
      {
        text: 'vuetify-loader',
        href: 'https://github.com/vuetifyjs/vuetify-loader',
      },
      {
        text: 'github',
        href: 'https://github.com/vuetifyjs/vuetify',
      },
      {
        text: 'awesome-vuetify',
        href: 'https://github.com/vuetifyjs/awesome-vuetify',
      },
    ],
    importantLinks: [
      {
        text: 'Documentation',
        href: 'https://vuetifyjs.com',
      },
      {
        text: 'Chat',
        href: 'https://community.vuetifyjs.com',
      },
      {
        text: 'Made with Vuetify',
        href: 'https://madewithvuejs.com/vuetify',
      },
      {
        text: 'Twitter',
        href: 'https://twitter.com/vuetifyjs',
      },
      {
        text: 'Articles',
        href: 'https://medium.com/vuetify',
      },
    ],
    whatsNext: [
      {
        text: 'Explore components',
        href: 'https://vuetifyjs.com/components/api-explorer',
      },
      {
        text: 'Select a layout',
        href: 'https://vuetifyjs.com/layout/pre-defined',
      },
      {
        text: 'Frequently Asked Questions',
        href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
      },
    ],
  }),
};
</script>

<style>
  .chat-message {
    font-family: "Arial", sans-serif;
    font-size: 16px;
    padding: 15px 20px;
    border-radius: 20px;
    background: #fff;
    border: 1px solid #eee;
    box-shadow: 0 3px 5px 0 #5f5f5f73;
    color: #16a085;
    margin-bottom: 15px;
  }
  .chat-message .info {
    color: #78909c;
    font-size: 13px;
    margin-bottom: 5px;
  }
</style>