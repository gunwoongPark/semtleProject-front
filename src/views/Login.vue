<template>
  <v-container id="loginPage">
    <LoginLogo></LoginLogo>
    <LoginForm></LoginForm>
  </v-container>
</template>

<script>
import LoginForm from "../components/LoginForm";
import LoginLogo from "../components/LoginLogo";
export default {
  name: "Login",
  components: {
    LoginForm,
    LoginLogo,
  },
};
</script>

<style scoped>

</style>