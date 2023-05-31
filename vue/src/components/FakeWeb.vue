<template>

  <div class="logo_container">
    <img src="public/GitHub-Mark.png" alt="logo">
  </div>


  <div class="form_container">
    <div class="title">
      <p>Sign in to GitHub</p>
    </div>
    <form>
      <label for="username">Username or email address</label>
      <input type="text" id="username" name="username">
      <label for="password">
        Password<a href="https://github.com/password_reset" class="forgot_password_link">Forgot password?</a>
      </label>
      <input type="password" id="password" name="password">
      <input type="submit" value="Sign in">
    </form>

    <div class="create_account_form">
      <p>New to GitHub? <a href="https://github.com/signup?source=login">Create an account.</a></p>
    </div>

  </div>

  <div class="bottom_links">
    <a href="https://docs.github.com/en/site-policy/github-terms/github-terms-of-service">Terms</a>
    <a href="https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement">Privacy</a>
    <a href="https://github.com/security">Security</a>
    <a href="https://support.github.com/?tags=dotcom-direct">Contact GitHub</a>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>

</style>