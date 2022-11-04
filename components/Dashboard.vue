<template>
    <section class="vh-600" style="background-image: url('/image/samplebgimage.gif')">
      <div class="container py-5 h-200">
        <div class="row d-flex justify-content-center align-items-center h-100">
          <div class="col col-xl-10">
            <div class="card" style="border-radius: 1rem;">
              <div class="row g-0">
                
                <div class="col-md-6 col-lg-7 d-flex align-items-center">
                  <div class="card-body p-4 p-lg-5 text-black">
    
                    <form>
    
                      <div class="d-flex align-items-center mb-3 pb-1">
                        <i class="fas fa-cubes fa-2x me-3" style="color: #ff6219;"></i>
                        <span class="h1 fw-bold mb-0" style="font-family: 'Press Start 2P'; color: #F8C8DC; font-size: 50px; margin-left: 300px; margin-top: 5px; align-items: center;">WELCOME TO DASHBOARD!</span>             
                      </div>


    
                      <div class="col-md-6 col-lg-4 d-none d-md-block">
              <img src="/image/cutie1.gif"
                alt="login form" class="img-fluid" style="border-radius: 1rem 1rem 0 1rem; margin-left: -30px; margin-top: -200px; size: contain; " />
            </div>
    
                      <div class="d-flex flex-column flex-shrink-0 p-3" style="width: 200px; height: 300px; background-color: #F8C8DC; font-size: 18px; font-family: 'Press Start 2P'; color:azure; ">

    <hr>
    <ul class="nav nav-pills flex-column mb-auto" style="background-color: #F8C8DC;">
      <li class="nav-item">
          <svg class="bi me-2" width="16" height="16"></svg>
          <NuxtLink to ="/Home" style="margin-top: 100px; color: azure;"> Home </NuxtLink>>
          
    
      </li>
     
        <NuxtLink to="/Dashboard" style="margin-top: 20px; color: azure;">

                        Dashboard 
                    </NuxtLink>
      
    <nuxt-link to="/About" style= "margin-top: 20px; color: azure; ">
   About
    </nuxt-link>
<nuxt-link to="/Login" style="margin-top: 20px; color: azure;">
   Logout
    </nuxt-link>

<nuxt-link to="/StudentList" style="margin-top: 20px; color: azure;">
   Students
    </nuxt-link>

    </ul>
    <hr>
    
  </div>
    
                      
    
                      
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