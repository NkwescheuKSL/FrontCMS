<template>
  <section style="background-color: rgba(125,54,100,0.99)">
    <div class="container py-5 h-100">
      <div class="row d-flex justify-content-center align-items-center h-100">
        <div class="col col-xl-10">
          <div class="card" style="border-radius: 1rem;">
            <div class="row g-0">
              <div class="col-md-6 col-lg-5 d-none d-md-block">
                <img
                    alt="login form"
                    class="img-fluid h-100"
                    src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-login-form/img1.webp"
                    style="border-radius: 1rem 0 0 1rem;"
                />
              </div>
              <div class="col-md-6 col-lg-7 d-flex align-items-center">
                <div class="card-body p-4 p-lg-5 text-black">

                  <form>

                    <div class="d-flex align-items-center mb-3 pb-1">
                      <i class="fas fa-cubes fa-2x me-3" style="color: #ff6219;"></i>
                      <span class="h1 fw-bold mb-0">Logo</span>
                    </div>

                    <h5 class="fw-normal mb-3 pb-3" style="letter-spacing: 1px;">Sign into your account</h5>

                    <div class="form-outline mb-4">
                      <!--                      <label class="form-label" for="form2Example17">Email address</label>-->
                      <input id="form2Example17" class="form-control form-control-lg" placeholder="Email" required
                             type="email"/>
                    </div>

                    <div class="form-outline mb-4">
                      <!--                      <label class="form-label" for="form2Example27">Password</label>-->
                      <input id="form2Example27" class="form-control form-control-lg" placeholder="Password" required
                             type="password"/>
                    </div>

                    <div class="pt-1 mb-4">
                      <button class="btn btn-dark btn-lg btn-block" type="button">Login</button>
                    </div>

                    <a class="small text-muted" href="#!">Forgot password?</a>
                    <p class="mb-5 pb-lg-2" style="color: #393f81;">Don't have an account? <a href="#!"
                                                                                              style="color: #393f81;">Register
                      here</a></p>
                    <a class="small text-muted" href="#!">Terms of use.</a>
                    <a class="small text-muted" href="#!">Privacy policy</a>
                  </form>

                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "login"
}
</script>

<style scoped>
input, button {
  border-radius: .5rem;
}
</style>
