<template>
<div>
    <div class="signup log-form"> 
        <form action="" class="formsign">
            <div class="form-group formitem">
            <label for="name">Email</label>
            <input type="text" class="form-control" id="name">
            </div>
            <div class="form-group formitem lastman">
            <label for="lname">Password</label>
            <input type="text" class="form-control" id="lname">
            </div>
            <button class="btn btn-block joinformbtn" type="submit">Login</button>
        </form> 
    </div>  
    <div class="forgo-pass">
      <a href="#">Forgot your password</a></br>
    </div>
    <div class="dnthvacc">
      <a href="join.html">Don't have an account? Click here to join us</a>
    </div>
</div>    
</template>
<script>
export default {
    
}
</script>
<style>
.signup{
     display: flex; 
   /* justify-content: center; */
    flex: 1;
    width: 100%;
    margin-bottom: 3rem;
	flex-direction:column;
	align-items: center;
}
.signup label{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    font-size: 1rem;
    font-weight: 600;
    width: 10rem;
}
.formitem{
    display: flex;
    width: 30rem;
}
.signup form button{
    text-align: center;
    margin: auto;
    width: 50%;
}
.joinformbtn{
    text-align: center;
    color: white;
    background-color: rgb(243, 121, 14);;
}
.joinformbtn:hover{
    text-align: center;
    color: white;
    background-color: rgb(236, 138, 52);
}
.signup form .lastman{
    margin-bottom: 2rem;
}
.forgo-pass{
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 0.4rem;
    width: 10rem;
}
.log-form{
    margin-bottom: 1rem;
}
.dnthvacc{
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 2rem;
    width: 20rem;
}
</style>