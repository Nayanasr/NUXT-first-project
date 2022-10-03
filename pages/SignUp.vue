<template>
<div>
   <h1>LOG-IN PAGE</h1>
   
  <form>

     <div class="mb-3">

    <label for="fullName" class="form-label">Full Name</label>

    <input type="name" class="form-control" id="fullName"/>
  </div>

  <div class="mb-3">

    <label for="exampleInputEmail1" class="form-label">Email address</label>

    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp"/>
    <div id="emailHelp" class="form-text">We'll never share your email with anyone else.</div>
  </div>

  <div class="mb-3">
    <label for="exampleInputPassword1" class="form-label">Password</label>

    <input type="password" class="form-control" id="exampleInputPassword1">
  </div>

  <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-input" id="exampleCheck1">

  </div>

   <div class="mb-3">

    <label for="confirmPassword" class="form-label">Confirm Password</label>

    <input type="password" class="form-control" id="confirmPassword"/>
  </div>

  <button type="submit" class="btn btn-primary">Submit</button>
 </form>
    
    <h4 @click="goToLogin" class="clickable">Already have an account..? Login one....!</h4>
 </div>
</template>

<script>
export default {
     methods:{
    goToLogin(){
      this.$router.push("/login")
    }
  }

}
</script>

<style>

</style>