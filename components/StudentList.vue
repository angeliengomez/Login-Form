<template>
    <section class="vh-600" style="background-image: url('/image/samplebgimage.gif')">
      <div class="container py-5 h-200">
        <div class="row d-flex justify-content-center align-items-center h-100">
          <div class="col col-xl-10">
            <div class="card" style="border-radius: 1rem;">
              <div class="row g-0">
                
                <div class="col-md-6 col-lg-7 d-flex align-items-center">
                  <div class="card-body p-4 p-lg-5 text-black">
    
                  
    
                      <div class="d-flex align-items-center mb-3 pb-1">
                        <i class="fas fa-cubes fa-2x me-3" style="color: #ff6219;"></i>
                        <span class="h1 fw-bold mb-0" style="font-family: 'Press Start 2P'; color: black; font-size: 50px; margin-left: 300px; margin-top: 5px; align-items: center;">Student List</span>
                      </div>

    
                      <div class="col-md-6 col-lg-4 d-none d-md-block">
              <img src="/image/cutie.gif"
                alt="pic1" class="img-fluid" style="border-radius: 1rem 1rem 0 1rem; margin-left: -30px; margin-top: -200px; size: contain; " />
            </div>
            <div>
              <b-table striped hover :items="students" style="color:black; font-family: 'Space Mono'; margin-left: 100px; font-size: 20px; text-align:center ;"></b-table>
  <form @submit.prevent="addStudent">

  <input v-model="newStudent" style="margin-left: 200px; font-family: 'Space Mono';">
  <button style="margin-left: 50px; margin-top: 20px; margin-bottom: 20px; font-family: 'Press Start 2P' ">ADD STUDENT</button>   
  <ul>
    <li v-for="student in students" :key="student.id" style="margin-left:300px; font-family: 'Space Mono'; color: black; font-size: 16px ">
    {{student.Information}}
    <button @click="removeStudent(student)">X</button>
    </li>
    </ul>> 

  </form>
    

  </div>

  
    

      
    
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
    
    </style>
    <script>
    let id = 0
    export default {
      data() {
        return {
          newStudent:'',
          students: [
         {id: id++, Information: 'Sample Student Name, BSIT'},
         {id: id++, Information: 'Sample Student Name1, BSIT'},
         {id: id++, Information: 'Sample Student Name2, BSIT'}
        ]

        }
        
      },
      methods:{
        addStudent(){
          
          this.students.push({id: id++, Information: this.newStudent});
          this.newStudent = ''
        },
        removeStudent(student)
        {
          this.students = this.students.filter((t) => t !== student)
        }
      }
     
    
    }
  </script>
 
    
