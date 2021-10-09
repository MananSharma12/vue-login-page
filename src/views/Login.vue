<template>
  <div id="sign-in">
    <h1>Sign In</h1>
    <input class="text-input" type="text" placeholder="Email ID" size="40"/> <br /><br />
    <input class="text-input" type="password" placeholder="Password" size="40"/> <br /><br />
    <a class="forgot-password" href="#">Forgot Password?</a> <br /><br />

    <a class="btn btn-dark">Login</a>
    <a class="btn btn-light">Sign Up</a>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#sign-in {
    max-width: 100vw;
}

h1 {
    font-weight: 100;
}

.text-input {
    height: 2rem;
    border-radius: 5px;
    display: inline-block;
}

.forgot-password {
    text-decoration: none;
    color: rgb(207, 0, 207);
    font-size: .75rem;
}

.btn {
    display: inline-block;
    text-decoration: none;
    padding: .5rem 2rem;
    border-radius: 5px;
    transition: all .2s;
    position: relative;
    font-size: 1.6rem;
    background-color: rgb(138, 1, 138);
    margin: .25rem;
}

.btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 1rem 2rem rgba(0, 0, 0, .2);
}

.btn-dark {
    color: #fff;
}

.btn-light {
    background-color: #fff;
    border: 1px solid rgb(138, 1, 138);
    color: rgb(138, 1, 138);
}

</style>