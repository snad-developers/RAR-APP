<template>
<div class = "main-container"> 

  <div class="child-div1">
  <h1><b>ANALYZE</b></h1>
  <p>TODAY'S CHALLANGES</p>
  
  <h1><b>ENVISION</b></h1>
  <P>TOMMOROW'S INNOVATION</P>

  </div>
  
   <div class="child-div4">
   
    
 
  <form  class="register">
   
    <div class="img">
      <img alt="" src="../assets/snadicon.png" />
   </div>
   <div class="child-div4">
      

   </div>
    <h2>Signup for new account </h2>
     <div class="forms main-container2" >
      <div class="child-4">
        
        <div style="margin:4px;">
  <label for="Select Questions">
     <select name="Select Questions" value="Select Questions" id="Select Questions" required class="user">
        <option value= "What is your favourite food/dish ?">What is your favourite food/dish ?</option>
        <option value="Who is your childhood hero ?">Who is your childhood hero ?</option>
        <option value="What is the name of your favourite pet ?">What is the name of your favourite pet ?</option>
        <option value="In what city you were born ?">In what city you were born ?</option>
        <option value="What is the name of your first school ?">What is the name of your first school ?</option>
   
     </select>
  </label>
  </div>
      <div class="" style="margin:4px;">
  <label for="Select Questions">
     <select name="Select Questions" value="Select Questions" id="Select Questions" required class="user">
        <option value= "What is your favourite food/dish ?">What is your favourite food/dish ?</option>
        <option value="Who is your childhood hero ?">Who is your childhood hero ?</option>
        <option value="What is the name of your favourite pet ?">What is the name of your favourite pet ?</option>
        <option value="In what city you were born ?">In what city you were born ?</option>
        <option value="What is the name of your first school ?">What is the name of your first school ?</option>
        </select>
        </label>
        </div>
   
     
 
      <div class="" style="margin:4px;">
  <label for="Select Questions">
     <select name="Select Questions" value="Select Questions" id="Select Questions" required class="user">
        <option value= "What is your favourite food/dish ?">What is your favourite food/dish ?</option>
        <option value="Who is your childhood hero ?">Who is your childhood hero ?</option>
        <option value="What is the name of your favourite pet ?">What is the name of your favourite pet ?</option>
        <option value="In what city you were born ?">In what city you were born ?</option>
        <option value="What is the name of your first school ?">What is the name of your first school ?</option>
   
     </select>
     </label>
     </div>
  
        <div class="" style="margin:4px;">
  <label for="Select Questions">
     <select name="Select Questions" value="Select Questions" id="Select Questions" required class="user">
        <option value= "What is your favourite food/dish ?">What is your favourite food/dish ?</option>
        <option value="Who is your childhood hero ?">Who is your childhood hero ?</option>
        <option value="What is the name of your favourite pet ?">What is the name of your favourite pet ?</option>
        <option value="In what city you were born ?">In what city you were born ?</option>
        <option value="What is the name of your first school ?">What is the name of your first school ?</option>

   
     </select>
     </label>

        <div class="" style="margin:4px;">
  <label for="Select Questions">
     <select name="Select Questions" value="Select Questions" id="Select Questions" required class="user">
        <option value= "What is your favourite food/dish ?">What is your favourite food/dish ?</option>
        <option value="Who is your childhood hero ?">Who is your childhood hero ?</option>
        <option value="What is the name of your favourite pet ?">What is the name of your favourite pet ?</option>
        <option value="In what city you were born ?">In what city you were born ?</option>
        <option value="What is the name of your first school ?">What is the name of your first school ?</option>
   
     </select>
  </label>
         </div>
      
      </div>
      </div>
      <div class="child-5" style="width:50%;">
  
 <div class="id" style="margin:8px;" >
    <label for="Give your answer"></label>
    <input type="text" placeholder="Give your answer"> 
      </div>
       <div class="id"  style="margin:8px;" >
            <label for="Give your answer"></label>
    <input type="text" placeholder="Give your answer">
      </div>
       <div class="id"  style="margin:13px;">
            <label for="Give your answer"></label>
    <input type="text" placeholder="Give your answer">
      </div>
       <div class="id"  style="margin:13px;">
            <label for="Give your answer"></label>
    <input type="text" placeholder="Give your answer">
      </div>
       <div class="id"  style="margin:13px;">
            <label for="Give your answer"></label>
    <input type="text" placeholder="Give your answer">
      </div>
         </div>
    


</div>
    <div class="my name">
   <router-link to="login"><button  class= "button" @click="Continue" style="width:70%" >Complete Registration</button></router-link>

</div> 
     

   


    
   
    </form>  
    <br>
     <br>
   </div> 
   
      
 
</div>


</template>

<script>
export default {
     // eslint-disable-next-line vue/multi-word-component-names
     name: 'registrationpage3',
}
// // eslint-disable-next-line no-unused-vars
// import {required, minLength, maxLength, between} from 'vuelidate/lib/validators'
// export default { 
//     // eslint-disable-next-line vue/multi-word-component-names
//      name: "login",
//      data:function () {
//        return {
//          UserId : '',
//          Password:'',
//          Entity:''

//        }
//      },
//      validations:{
//          // eslint-disable-next-line no-undef
//          UserId:{
//            required,
//            minLength: minLength(8),
//            maxLength: maxLength(16),

//          },
//          Password:{
//            required,
//            minLength: minLength(8),
//            maxLength: maxLength(16),
//          }
//      },
//      methods:{
//            validationStatus: function(validation) {
//              return typeof validation !="undefined" ? validation.$error : false;
//            },

//        Submit: function(){
//          this.$v.$touch();
//          if (this.$v.$pending || this.$v.$error) return;

//          alert('Data Submit');


//        },
//      }  
// }

</script> 

<style>
.username{
   margin:10px;
   width:74%;

}
.main-container2{
   display: flex;
    flex-direction: row;
    justify-content: space-around;
}
.main-container{
  display: flex;
  flex-direction: row;
    justify-content: center;
}
.child-div1{
  width: 50%;
  display: flex;
    flex-direction: column;
    justify-content: center;
}
.child-div2{
  width: 35%;
}

div{
  text-align: center;
}
.backbtn{
    text-align: left;
}
h1{
  /* text-align: center; */
}
input[type=text]{
    
    padding: 12px 20px;
    border: 1px solid;
    border-radius: 20px;
    text-align: center;
     font-family: sans-serif;
   
}
input[type=password]{

    padding: 12px 20px;
    border: 1px solid;
    border-radius: 20px;
    text-align: center;
     font-family: sans-serif;
}
select{
    width: 28%;
    padding: 12px 20px;
    border: 1px solid;
    border-radius: 20px;
    text-align: center;
     font-family: sans-serif;
}
input[type=button]{
    width: 10%; 
    padding: 12px 20px;
    border: 1px solid;
    border-radius: 20px;
    text-align: center;
    background-color: rgb(119, 6, 6);
    color: white;
     font-family: sans-serif;
}
.button{
    
  width: 100%;
  margin-bottom: 10px;
  padding: 10px;
  border-radius: 50px;
  border: 2px solid #dddddd;
  background: #634ed8;
  outline: none;
  transition: border-color 0.5s;
  font-family: sans-serif;
}
.child-div4{
    width: 50%;
}
.button1{
    
    padding: 12px 20px;
    border: 1px solid;
    border-radius: 20px;
    text-align: center;
    background-color:  rgb(15, 6, 119);
    color: white;
     font-family: sans-serif;
     transition: 0.5s;
}
p::after{
  content: " ";
  position: absolute;
  display: block;
  left: 46%;
  bottom: 0%;
  width:8%;
  height: 2px;
  background-color: aqua;
   font-family: sans-serif;
}
.img{
  text-align: left 2px;
  margin-left:-10px ;
  margin-bottom: 10px;
}

.backbtn{
  align-items: baseline;
   font-family: sans-serif;
}
input[type="checkbox"] {
  -webkit-appearance: checkbox;
     -moz-appearance: checkbox;
          appearance: checkbox;
  display: inline-block;
  font-family: sans-serif;
 width: auto;
}
.FG{
   text-justify: auto;
   text-align: right;
}
body{
  background:-webkit-linear-gradient(left ,white,rgb(238, 212, 216)) ;
  margin: 15px;
  margin-top: 50px;
  position: relative;
   font-family: sans-serif;

}  



  
  

  

p{
 margin:-2px;
 font-size: 25px;
}
h1{
  margin:-2px;
  font-size: 70px;
}
.register{
    width:77%;
  height: 97%;
   max-width: 600px;
   /* max-height: 5%; */
   margin: 10px auto;
   border-radius: 15px;
   overflow: hidden;
   box-shadow: 0 0 15px rgba(0,0,0,0.15);  
   /* margin-left:519px ; */
   margin-bottom: 0%;
   font-family: sans-serif;
   background-color:white;
   
}
.button6{
 background: #634ed8;
    width: 70%;
    padding: 6px;
    border-radius: 25px;
}


.imgs{
  display: block;
  max-width: 125px;
  margin: 0 auto;
}
.forms{
  padding: 30px;


}
.forms1{
  margin-bottom: 0px;
  color: #c51414;
}
.user{
  width: 100%;
  margin-bottom: 10px;
  padding: 10px;
  border-radius: 50px;
  border: 2px solid #dddddd;
  background: #ffffff;
  outline: none;
  transition: border-color 0.5s;
  font-family: sans-serif;

}



.user::placeholder{
  color: #aaaaaa;

}
h1{
  /* font-family: sans-serif; */
}
.regis{
   box-sizing: border-box;
  font-family: sans-serif;
  margin-right: 75%;
  background: #eeee;
  margin-left: 5%;
  border-radius: 25px;


  
  
}
.form{
  background-color: #dddddd;
}
h1{
  /* text-align: center  ;
  margin-left:-600px;
  font-size:50px;
  margin-top: 20px; */
  

}
p{
  /* text-align: center  ;
  margin-left:-600px;
  font-size: 30px; */
}
.main-div{
      display: flex;
    justify-content: space-around;
}
p{
  margin: 0px;
}
.child-div1{
  margin:0px !important
}
.company{
   margin:10px;
}




</style>
