<template>
  <div class="flex-center">
    <div class="login-card">
      <div class="new acc">Create a new account</div>
      <div class="nav">
        <input placeholder="E-mail" type="text" id="name">
        <input placeholder="Username" type="text" id="name">
        <input placeholder="password" type="password" id="password">
      </div>

    </div>
  </div>
</template>

<style lang="scss" scoped>
    .login {
    &-card {
        width: 360px;
        background: white;
        box-shadow: 0 0 30px rgba(0, 0, 0, 0.1);
        padding: 3rem;
    }
}
.from-group {
        display: flex;
        flex-direction: column;
     label {
    display: block;
    margin: 10px;
    }
}

.sign-btn {
    border-radius: 5px;
    background: cornflowerblue;
    margin-top: 5px;
}

.input-name {
    margin-top: 5px;
    margin-bottom: 5px;
}

.login-card {
    justify-content: space-around;

}
.nav {
    display: flex;
    flex-direction: column;
    margin: 10px;
}

</style>
