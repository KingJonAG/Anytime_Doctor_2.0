<template>
 <section class="testimonials text-center bg-light testMnial">
    <div class="row">
        <div class="col-lg-4 docitem">
          <div class="testimonial-item mx-auto mb-5 mb-lg-0">
            <img class="img-fluid rounded-circle mb-3" src="../../assets/img/Pic15.jpg" alt="">
            <h5>Hospital 1</h5>
            <div class="availbledoc">
                <a href="">Book Test</a>
            </div>
          </div>
        </div>
    </div>
 </section>      
</template>
<script>
export default {
  
}
</script>
<style>
.docitem{
    margin-bottom: 2.5rem;
}
.testMnial{
    padding-top: 4rem;
    padding-bottom: 5rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.docpaneltext{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: rgb(243, 121, 14);
    font-weight: 300;
    font-size: 2.5rem;
}
.docpanelsubtext{
    font-size: 1rem;
}
.testimonials {
  padding-top: 7rem;
  padding-bottom: 7rem;
}

.testimonials .testimonial-item {
  max-width: 18rem;
}

.testimonials .testimonial-item img {
  max-width: 12rem;
  box-shadow: 0px 5px 5px 0px #adb5bd;
}
.avilblebtn{
    width: 1rem;
    height: 1rem;
    background-color: rgb(21, 235, 39);
    border-radius: 50%;
    align-self: center;
    margin: 0.5rem;
}
.availbledoc{
    display: flex;
    justify-content: center;
    margin: 1rem;
    margin-left: 0;
}
.availbledoc a{
    text-decoration: none;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: rgb(45, 106, 218);
    color: white;
    padding: 0.7rem;
    border-radius: 20px;
}
.availbledoc a:hover{
    background-color: rgb(243, 121, 14);
}
</style>