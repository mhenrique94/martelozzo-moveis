<template>
  <div class="wa-icon">
    <a href="https://api.whatsapp.com/send?phone=5515981630646&text=Ol%C3%A1!">
      <v-icon color="green" icon="mdi-whatsapp" size="56"></v-icon>
    </a>
    <v-tooltip activator="parent" location="start"
      >Entre em contato pelo Whatsapp!</v-tooltip
    >
  </div>
</template>
<style>
.wa-icon {
  background-color: white;
  border-radius: 50%;
  padding: 8px;
  color: #25d366;
  z-index: 2000;
}

a,
a:visited,
a:active,
a:link {
  text-decoration: none !important;
  text-decoration-color: #25d366 !important;
}
</style>
