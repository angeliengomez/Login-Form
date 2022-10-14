<template>
<section class="vh-200" style="background-image: url('/image/samplebgimage.gif')">
  <div class="container py-5 h-100">
    <div class="row d-flex justify-content-center align-items-center h-100">
      <div class="col col-xl-10">
        <div class="card" style="border-radius: 1rem; background-color: gray;">
          <div class="row g-0">
            <div class="col-md-6 col-lg-5 d-none d-md-block">
                
              <img src="/image/bg12.gif"
               
                alt="login form" class="img-fluid" style="border-radius: 1rem 1rem 0 1rem; margin-left: 20px; margin-top: 180px; size: contain;" />
            </div>
          
          
            
            <div class="col-md-6 col-lg-7 d-flex align-items-center">
              <div class="card-body p-4 p-lg-5 text-black">

                <form>

                  <div class="d-flex align-items-center mb-3 pb-1">
                    <i class="fas fa-cubes fa-2x me-3" style="color: #ff6219;"></i>
                    <span class="h1 fw-bold mb-0" style="font-family: 'Press Start 2P'; color:#F8C8DC; font-size: 50px; margin-left: 30px; margin-top: 5px">WELCOME!</span>
                  </div>
                  <div class="col-md-6 col-lg-5 d-none d-md-block">
              <img src="/image/cutie1.gif"
                alt="login form" class="img-fluid" style="border-radius: 1rem 1rem 0 1rem; margin-left: -530px; margin-top: -300px; size: contain; " />
            </div>
                  <div class="col-md-6 col-lg-5 d-none d-md-block">
              <img src="/image/cutie.gif"
                alt="login form" class="img-fluid" style="border-radius: 1rem 1rem 0 1rem; margin-left: 380px; margin-top: -380px; size: contain; " />
            </div>

                  <h5 class="fw-normal mb-3 pb-3" style="letter-spacing: 1px; font-family: 'Space Grotesk';  color:  #cfcfc4 ">Sign in to your account :'> </h5>

                  <div class="form-outline mb-4">
                    <input type="email" id="form2Example17" class="form-control form-control-lg"  style="animation-name: sample; animation-duration: 4s; animation-iteration-count: infinite; animation-direction: reverse;"/>
                    <label class="form-label" for="form2Example17" style="font-family: 'Space Grotesk'; color:#F8C8DC; margin-top: 10px">Email address</label>
                  </div>

                  <div class="form-outline mb-4">
                    <input type="password" id="form2Example27" class="form-control form-control-lg" style="animation-name: sample; animation-duration: 4s; animation-iteration-count: infinite; animation-direction: reverse;" />
                    <label class="form-label" for="form2Example27" style="font-family: 'Space Grotesk'; color:#cfcfc4; margin-top: 10px">Password</label>
                  </div>

                  <div class="pt-1 mb-4">
                    <button class="btn btn-secondary btn-lg btn-block" type="submit"  style="font-family: 'Press Start 2P'; color:#F8C8DC; animation-name: sample1; animation-duration: 10s; animation-iteration-count: infinite; animation-direction: reverse; ">
                      <NuxtLink to="/Home" style="color:#F8C8DC">
                        LOGIN
                    </NuxtLink>
                    </button>
                 
                  </div>

                  <a class="fw-normal mb-3 pb-3" href="#!" style="font-family: 'Space Grotesk'; color: #cfcfc4; font-size: 18px">Forgot password?</a>
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
<style>
section{
    background-image: url("/image/background.gif");
}
@keyframes sample{
    from {background-color: white;}
  to {background-color: #F8C8DC;}
}
@keyframes sample1{
    from {background-color: white;}
  to {background-color: #302c2d;}
}
</style>