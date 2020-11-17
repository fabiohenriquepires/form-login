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
      <button class="btn btn-green">Create New Account</button>  
    </form>
    <!--<p><a>Create a Page</a>for a celebrity, band or business.</p>-->
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
  border-radius: 8px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

input {
  padding: 14px 16px;
  font-size: 17px;
  width: 100%;
  display: block;
  margin-bottom: 12px;
  border-radius: 6px;
  border: 1px solid #dddfe2;
}

.btn {
  background: #166fe5;
  color: #fff;
  border: none;
  border-radius: 6px;
  line-height: 48px;
  width: 100%;
  display: block;
  font-weight: bold;
  font-size: 20px;
  cursor: pointer;
}

.btn-green {
  background: #42b72a;
  margin-right: auto;
  margin-left: auto;
  width: auto;
  display: inline-block !important ;
  padding: 0 16px;
  margin-bottom: 10px;
}

.forget-password {
  margin-top: 24px;
  margin-bottom: 24px;
}

a {
  text-align: center;
  text-decoration: none;
  color: #166fe5;
  font-size: 14px;
}

.divider {
  width: 100%;
  margin-bottom: 24px;
  background: blue;
  border-bottom: 1px solid #dadde1;
}
</style>