<template>
  <div class="form-container">
    <form>
      
      <input type="email" id="email" name="email" placeholder="Email or Phone Number">
      <input type="password" id="password" name="password" placeholder="Password">

      <button class="btn">Log In</button>

      <div class="forget-password">
        <a href="#">Forgot Password?</a>  
      </div>
      <div class="divider">
      </div>
      <button>Create New Account</button>  
    </form>
  </div>
</template>

<script>
export default {
  name: "FormLogin"
}
</script>

<style scoped>

form {
  width: 395px;
  padding: 15px;
  background: #fff;
}

input {
  padding: 14px 16px;
  font-size: 17px;
  width: 100%;
  display: block;
  margin-bottom: 12px;
}

.btn {
  background: #166fe5;
  color: #fff;
  border: none;
  border-radius: 6px;
  line-height: 48px;
  width: 100%;
  display: block;
  margin-bottom: 24px;
  font-weight: bold;
  font-size: 20px;

}

.forget-password {
  margin-bottom: 24px;
}
a {
  text-align: center;
  text-decoration: none;
  color: #166fe5;
}

.divider {
  width: 100%;
  margin-bottom: 24px;
  background: blue;
  border-bottom: 1px solid #dadde1;
}
</style>