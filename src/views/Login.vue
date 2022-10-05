<template>
  <div class="root">
    <div>
      <div class="formLogin">
        <h1>Login</h1>
        <p>
          welcome to Chat app, please login to continue chatting with your
          friends
        </p>

        <div class="formLogin__group">
          <b-input-group  prepend="Username" >
            <b-form-input></b-form-input>
          </b-input-group>
          <div class="form-bnt">
          <b-button variant="success" block size="lg" class="btn-form">Login</b-button>
  
          </div>
        </div>

      </div>
    </div>
    <div class="img">
      <img src="https://picsum.photos/500/500" alt="img" />
    </div>
  </div>
</template>

<script>
export default {
  name: "LoginComponent",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.root {
  max-width: 1000px;
  display: flex;
  justify-content: space-between;
  margin: 0 auto;
  margin-top: 100px;
  background-color: aliceblue;
  padding: 30px;
  border-radius: 20px;
  box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}
.formLogin > h1 {
  font-size: 4rem;
}
.formLogin > p {
  font-size: 1.5rem;
  margin-top: 1rem;
}
.formLogin__group {
  margin-top: 2.5rem;
  padding: 2rem;
}
.form-bnt{
    margin-top: 2rem;
    display: flex;
    justify-content: center;;
}
.btn-form{
    width: 100%;
}
</style>
