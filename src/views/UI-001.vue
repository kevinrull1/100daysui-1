<template>
  <div class="flex-center">
    <div class="login-card">
        <form class="login-form">
            <h1>Create a new account</h1>
            <div class="from-group">
                <label class="input-name" for="name">Your E-mail</label>
                <input type="text" id="name">
            </div>
            <div class="from-group">
                <label class="input-name"  for="name">Your Username</label>
                <input type="text" id="name">
            </div>
            <div class="from-group">
                <label  class="input-name" for="password">Password</label>
                <input type="password" id="password">
            </div>
            <button class="sign-btn" type="submit">Sign up</button>
        </form>
    </div>
  </div>
</template>

<style lang="scss" scoped>
    .login {
    &-card {
        width: 360px;
        background: white;
        box-shadow: 0 0 30px rgba(0, 0, 0, 0.1);
        padding: 2rem;
    }
}
.from-group {
        display: flex;
        flex-direction: column;
     label {
    display: block;
    }
}

.sign-btn {
 margin-top: 5px;
}

.input-name {
    margin-top: 5px;
    margin-bottom: 5px;
}

.login-card {
    
}

</style>
