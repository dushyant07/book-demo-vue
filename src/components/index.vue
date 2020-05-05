<template>
    <div class="homefile">
        <!--Header Information-->
		  <header class="header" id="home">
		    <div class="container">
		    	<div class="row align-items-center justify-content-between d-flex">
			      <div id="logo">
			        <a href="index.html"><h2>{{ logo }}</h2></a>
			      </div>
			      <nav id="nav-menu-container">
			        <ul class="nav-menu">
			          <li class="menu-active"><a href="#home">Home</a></li>
			          <li><a href="#about">Book in Details</a></li>
			          <li><a href="#library">Library Details</a></li>
			          <li><a href="#review">Review</a></li>
			          
			        </ul>
			      </nav><!-- #nav-menu-container -->		    		
		    	</div>
		    </div>
		  </header>

			<!-- Book Detail -->
			<section class="banner-area" id="home">	
				<div class="container">
					<div class="row fullscreen d-flex align-items-center justify-content-start">
						<div class="banner-content col-lg-7">
							<h5 class="text-white text-uppercase">Author: Norman, Donald A.</h5>
							<h1 class="text-uppercase">
								The design of everyday things				
							</h1>
							<p class="text-white pt-20 pb-20">
								Psychology of everyday things The design of everyday things Revised and expanded edition
							</p>
							<a href="#" class="primary-btn text-uppercase" v-on:click="buynowClick">Buy Now for 17.99 USD</a>
						</div>
						<div class="col-lg-5 banner-right">
							<img class="img-fluid" src="img/header-img.png" alt="">
						</div>												
					</div>
				</div>
			</section>
				

			<!--Book in details-->
			<section class="section-gap info-area" id="about">
				<div class="container">				
					<div class="single-info row mt-40 align-items-center">
						<div class="col-lg-6 col-md-12 text-center no-padding info-left">
							<div class="info-thumb">
								<img src="img/about-img.jpg" class="img-fluid info-img" alt="">
							</div>
						</div>
						<div class="col-lg-6 col-md-12 no-padding info-rigth">
							<div class="info-content">
								<h2 class="pb-30">Nicole Caputo</h2>
								<p>
									The Design of Everyday Things shows that good, usable design is possible. The rules are simple, make things visible, exploit natural relationships that couple function and control, and make intelligent use of constraints. The goal, guide the user effortlessly to the right action on the right control at the right time.								
								</p>
								<br>
								<p>
									Edition : 5								
								</p>
								<p>
									Published Date : Nov. 05, 2013								
								</p>
								<br>
								<img src="img/signature.png" alt="">
								</div>
						</div>
					</div>
				</div>
			</section>
		
			<!-- Library Heading -->
			<section class="fact-area relative section-gap" id="library">
				<div class="overlay overlay-bg"></div>
				<div class="container">
					<div class="row d-flex justify-content-center">
						<div class="menu-content pb-40 col-lg-8">
							<div class="title text-center">
								<h1 class="mb-10">Libraries</h1>
							</div>
						</div>
					</div>						
				</div>	
			</section>
			
			<!--Library detail -->
			<section class="counter-area">
				<div class="container">
					<div class="row">
						<div class="col-lg-3 col-md-6">
							<div class="single-counter">
								<h3>Bodleian <br> Library</h3>
								<p><b>Checkin Date</b>: 2021-02-11</p>								
							</div>
						</div>
						<div class="col-lg-3 col-md-6">
							<div class="single-counter">
								<h3>Troy Public <br> Library</h3>
								<p><b>Checkin Date</b>: 2018-01-04</p>								
							</div>
						</div>
						<div class="col-lg-3 col-md-6">
							<div class="single-counter">
								<h3>Bibliotheca <br> Alexandrina</h3>
								<p><b>Checkin Date</b>: 2017-02-03</p>								
							</div>
						</div>
						<div class="col-lg-3 col-md-6">
							<div class="single-counter">
								<h3>Bodleian <br> Library</h3>
								<p><b>Checkin Date</b>: 2021-02-11</p>								
							</div>
						</div>												
					</div>
				</div>	
			</section>

			<!--Reviews -->
			<section class="testomial-area section-gap" id="review">
				<div class="container">
					<div class="row d-flex justify-content-center">
						<div class="menu-content pb-60 col-lg-8">
							<div class="title text-center">
								<h1 class="mb-10">REVIEWS</h1>
								<p>Let's See - Who are in extremely love with this book</p>
							</div>
						</div>
					</div>						
					<div class="row">
						<div class="active-tstimonial-carusel">
							<div class="single-testimonial item">
								<img class="mx-auto" src="img/t1.png" alt="">
								<p class="desc">
									Even classics can be updated and improved ... Highly recommended.
								</p>
								<h4>Choice</h4>
							</div>
							<div class="single-testimonial item">
								<img class="mx-auto" src="img/t2.png" alt="">
								<p class="desc">
									This book changed the field of design. As the pace of technological change accelerates, the principles in this book are increasingly important. The new examples and ideas about design and product development make it essential reading.
								</p>
								<h4>Patrick Whitney</h4>
								<p>
									 Dean, Institute of Design, and Steelcase
								</p>
							</div>
							<div class="single-testimonial item">
								<img class="mx-auto" src="img/t3.png" alt="">
								<p class="desc">
									Twenty-five years ago The Design of Everyday Things was instrumental in orienting my approach to design. With this latest revised and expanded edition, Don Norman has given me a host of new ideas to explore as well as reminding me of the fundamental principles of great and meaningful design. Part operating manual for designers and part manifesto on the power of designing for people, The Design of Everyday Things is even more relevant today than it was when first published.
								</p>
								<h4>Tim Brown</h4>
								<p>
									CEO, IDEO, and author of Change by Design
								</p>
							</div>	
							<div class="single-testimonial item">
								<img class="mx-auto" src="img/t1.png" alt="">
								<p class="desc">
									Design may be our top competitive edge. This book is a joy--fun and of the utmost importance.
								</p>
								<h4>Tom Peters</h4>
								<p>
									Author of In Search of Excellence
								</p>
							</div>
																			
						</div>
					</div>
				</div>	
			</section>

			<!-- Footer -->		
			<footer class="footer-area section-gap">
				<div class="container">
					<div class="row">
						<div class="col-lg-5 col-md-6 col-sm-6">
							<div class="single-footer-widget">
								<h6>About Us</h6>
								<p>
									The Design of Everyday Things shows that good, usable design is possible. The rules are simple, make things visible, exploit natural relationships that couple function and control, and make intelligent use of constraints. The goal, guide the user effortlessly to the right action on the right control at the right time
								</p>
								
							</div>
						</div>
						<div class="col-lg-5  col-md-6 col-sm-6">
							<div class="single-footer-widget">
								<h6>Newsletter</h6>
								<p>Stay update with our latest</p>
								<div class="" id="mc_embed_signup">
									<form target="_blank" novalidate="true" action="https://spondonit.us12.list-manage.com/subscribe/post?u=1462626880ade1ac87bd9c93a&amp;id=92a4423d01" method="get" class="form-inline">
										<input class="form-control" name="EMAIL" placeholder="Enter Email" v-model="message">
			                            	<button class="click-btn btn btn-default"><i class="fa fa-long-arrow-right" aria-hidden="true"></i></button>
			                            	<div style="position: absolute; left: -5000px;">
												<input name="b_36c4fd991d266f23781ded980_aefe40901a" tabindex="-1" value="" type="text">
											</div>

										<div class="info"></div>
									</form>
								</div>
							</div>
						</div>						
						<div class="col-lg-2 col-md-6 col-sm-6 social-widget">
							<div class="single-footer-widget">
								<h6>Follow Us</h6>
								<p>Let us be social</p>
								<div class="footer-social d-flex align-items-center">
									<a href="#"><i class="fa fa-facebook"></i></a>
									<a href="#"><i class="fa fa-twitter"></i></a>
									<a href="#"><i class="fa fa-dribbble"></i></a>
									<a href="#"><i class="fa fa-behance"></i></a>
								</div>
							</div>
						</div>							
					</div>
				</div>
			</footer>
    </div>
    
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
