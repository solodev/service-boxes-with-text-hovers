# service-boxes-with-text-hovers
Showcase key services with branded-graphics; users can get more information by hovering over the boxes.

## Tutorial
For detailed instruction's, view Solodev's [Service Boxes with Text Hovers](https://www.solodev.com/blog/web-design/how-to-create-service-boxes-with-text-hovers.stml) article.

## Demo
  		  
Try out a working example on [JSFiddle](http://jsfiddle.net/solodev/fcuypqes/32/).

## HTML

The tutorial contains the following basic HTML markup.

```
<section class="section-boxes">
        <div class="container">
            <div class="row">
                <div class="col-12">
                     <h2 class="text-center text-uppercase w-100">LunarXP</h2>
                        <p class="text-center mt-3 mb-4 w-100 h5">
                            At LunarXP, we’re dreamers and explorers. We’ve always looked up for purpose – and we’ve never looked back. 
                            As a company, we believe that the future of mankind lies beyond earth and in the stars. 
                            Together, we can make a better tomorrow for all of us. It starts with one small step.					
                        </p>
                </div>
                <div class="col-xl-4 col-sm-6">
                    <div class="box-lunar lunarxp-launch-site p-3 mt-3 mt-sm-4 mt-lg-0 d-flex align-items-center justify-content-center flex-column position-relative w-100">
                        <p class="font-weight-bold primary-text text-uppercase">LunarXP Launch Site</p>
                        <div class="box-hover lunarxp-launch-site bg-dark p-3 p-lg-4 top-0 left-0 text-white position-absolute w-100 h-100">
                            <h2 class="text-center mb-3 text-uppercase">LunarXP Launch Site</h2>
                            <p class="text-white text-center mb-0">Formerly NASA’s International Space Station, the LunarXP Launch Site is the first stop on the standard route to the lunar surface.</p>
                            <a href="http://www.lunarxp.com/" class="btn btn-dark d-block mt-3 mx-auto text-white border-white">Learn More</a>
                        </div><!-- .box-hover -->
                    </div><!-- .box-lunar-->
                </div>
                <div class="col-xl-4 col-sm-6">
                    <div class="box-lunar lunarxp-control-center p-3 mt-3 mt-sm-4 mt-lg-0 d-flex align-items-center justify-content-center flex-column position-relative w-100">
                        <p class="font-weight-bold primary-text text-uppercase">LunarXP Control Center</p>
                        <div class="box-hover lunarxp-control-center p-3 p-lg-4 bg-dark top-0 left-0 text-white position-absolute w-100 h-100">
                            <h2 class="text-center mb-3 text-uppercase">LunarXP Control Center</h2>
                            <p class="text-white text-center mb-0">Our control center is where directors and engineers supervise the countdown for all rocket lunar launches.</p>
                            <a href="http://www.lunarxp.com/" class="btn btn-dark d-block mt-3 mx-auto text-white border-white">Learn More</a>
                        </div><!-- .box-hover -->
                    </div><!-- .box-lunar-->
                </div>
                <div class="col-xl-4 col-sm-6">
                    <div class="box-lunar lunarxp-rocket-center p-3 mt-3 mt-sm-4 mt-lg-0 d-flex align-items-center justify-content-center flex-column position-relative w-100">
                        <p class="font-weight-bold primary-text text-uppercase">LunarXP Rocket Center</p>
                        <div class="box-hover lunarxp-rocket-center p-3 p-lg-4  bg-dark top-0 left-0 text-white position-absolute w-100 h-100">
                            <h2 class="text-center mb-3 text-uppercase">LunarXP Rocket Center</h2>
                            <p class="text-white text-center mb-0">Our fleet of advanced spacecraft have revolutionized the lunar economy. These amazing vessels are also paving the way for reaching Mars in the next decade. </p>
                            <a href="http://www.lunarxp.com/" class="btn btn-dark d-block mt-3 mx-auto text-white border-white">Learn More</a>
                        </div><!-- .box-hover -->
                    </div><!-- .box-lunar-->
                </div>
            </div><!-- .row-->
        </div><!-- .container-->
    </section>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
<link rel="stylesheet" href="style.css">
<link href="https://fonts.googleapis.com/css?family=Space+Mono&display=swap" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
```
