<template>
 <section class="testimonials text-center bg-light testMnial">
    <div class="row">
        <div class="col-lg-4 docitem">
          <div class="testimonial-item mx-auto mb-5 mb-lg-0">
            <img class="img-fluid rounded-circle mb-3" src="../../assets/img/Pic10.jpg" alt="">
            <h5>Margaret E.</h5>
            <p class="font-weight-light mb-0 docpanelsubtext">Doctor 1</p>
          </div>
        </div>
    </div>
 </section>      
</template>
<script>
export default {
    data:function(){
        return{
        }
    }
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
</style>