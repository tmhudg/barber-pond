<template>

  <div class="">

    <header class="masthead  text-center" style="padding-bottom: 29rem; background-size: cover">
      <div class="overlay" >
      	<div class="row">
    			<div class="col-lg-10">
  	      		<img src="img/SiteName.png" class="rounded img-fluid" style="background-color: white; padding: 1rem; "/>
  		  		<h1>
              <a v-bind:href="'tel:1-' + phone">{{ phone }}</a>
            </h1>
            <h4>You've got stuff? We've got space</h4>
	      	</div>
      	</div>
      </div>
    </header>

    <section class="info">
      <div class="container">
        <div class="row">
          <div class="col">
            <div class="header">
              <h3>Barber Pond Road Self Storage</h3>
            </div>
            <img src="img/couple-outside-units.jpg" class="img-fluid float-lg-right" style="min-width: 400px;"/>
          </div>
          <div class="col">
            <div class="header">
              <h3>Rest easy knowing your items are safe</h3>
            </div>
            <p>If you’re looking for an affordable and reputable storage facility, your search ends at Barber Pond Road Self Storage.</p>
            <p>Come to us for safe and secure warehouse spaces in Pownal, VT. Many of our units can be accessed from both sides and are open 24 hours a day. </p>
            <p>We’re family owned and operated, and committed to giving you cost-effective, quality, and safe storage solutions.</p>
          </div>
        </div>
      </div>
    </section>


    <section>

	   	<div class="container">
		    <div class="card mb-3 green-card" >
				<div class="card-body">
					<h2 class="card-title text-center">Pay for 1 year up front and get 1 month FREE. Call us now for more details!</h2>
					<h2 class="text-center"><a v-bind:href="'tel:1-' + phone">{{ phone }}</a></h2>
				</div>
			</div>
	   	</div>
	   	<div class="container">
		    <div class="card mb-3 border-0" >
				<div class="card-body">
					<h1 class="card-title text-center">Affordable Storage You Can Trust</h1>
					<h2 class="text-center">Get peace of mind – and save money</h2>
				</div>
			</div>
	   	</div>
	   	<div class="container">
		    <div class="card-deck" >
			    <div class="card green-card">
				    <div class="card-body">
						<div class="float-left">
              <fa style="color: white" size="3x" :icon="['fas','dollar-sign']"/>
            </div>
						<h2 class="card-title text-center">Get 1 month FREE</h2>
						<p>We want to make long term rental easy and affordable.</p>
						<p>When you pay the rent for the entire year up front, we give you 1-month FREE service.</p>
						<p>Call to find out more about this great deal!</p>
				    </div>
			    </div>
			    <div class="card green-card">
				    <div class="card-body">
						<div class="float-left">
              <fa style="color: white" size="3x" :icon="['fas','thumbs-up']"/>
            </div>
						<h2 class="card-title text-center">Quality Service</h2>
						<p>Barber Pond Road Self Storage gives you a clean, affordable storage facility – with the safety you expect.</p>
						<p>You have access to your unit whenever you need. Our flexible start dates means that you can choose when rent is due during the month.</p>
				    </div>
			    </div>
			    <div class="card green-card">
				    <div class="card-body">
  						<div class="float-left">
                <fa style="color: white" size="3x" :icon="['fas','check']"/>
              </div>
  						<h2 class="card-title text-center">Why Choose Us</h2>
              <ul>
  						 	<li>Lowest price in the area</li>
  						 	<li>Safe storage</li>
  						 	<li>Clean and well-maintained facility</li>
  						 	<li>Many units can be accessed from both sides</li>
  						 	<li>24-hour access</li>
  						 	<li>No prorations</li>
  						 	<li>Personal care</li>
  						 	<li>10 x 10 and 10 x 20 units</li>
              </ul>
              <p>We sell locks too!</p>
				    </div>
			    </div>
		    </div>
	   	</div>
    </section>

    <!-- Icons Grid -->
    <section class="features-icons text-center">
		<div class="container">
			<div class="row">
				<div class="col-lg-6">
					<div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
						<div class="features-icons-icon d-flex">
							<fa class="barber-green m-auto" size="3x" :icon="['fas','phone']"/>
						</div>
						<h3>Contact Us</h3>
						<p>1166 Barber Pond Road</p>
						<p>Pownal, VT 05261</p>
						<p><a v-bind:href="'tel:1-' + phone">{{ phone }}</a></p>
					</div>
				</div>
				<div class="col-lg-6">
					<div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
            <div class="features-icons-icon d-flex">
              <fa class="barber-green m-auto" size="3x" :icon="['fas','map-marker-alt']"/>
            </div>
            <h3>Find Us</h3>
            <p>Click to open a new Google Maps window with our location</p>
            <a class="btn btn-primary" target="_blank" href="https://www.google.com/maps/place/Barber+Pond+Road+Self+Storage+%E2%80%93+Storage+%7C+Pownal,+VT/@42.7953519,-73.2025917,17z/data=!4m12!1m6!3m5!1s0x89e0bc3ea47d0337:0xcf8520fbf732e0a6!2sBarber+Pond+Road+Self+Storage+%E2%80%93+Storage+%7C+Pownal,+VT!8m2!3d42.795348!4d-73.200403!3m4!1s0x89e0bc3ea47d0337:0xcf8520fbf732e0a6!8m2!3d42.795348!4d-73.200403" role="button">View Map</a>
          </div>
        </div>
      </div>
    </div>
	</section>

    <!-- Image Showcases -->
    <section class="showcase">
		<div class="container">
			<div class="row">
				<div class="header col-12">
					<h1>Payment Methods</h1>
				</div>
			</div>
			<div class="row">
				<div class="col-sm-1">
					<img src="img/personal_check.jpg"/>
				</div>
				<div class="col-sm-1">
					<img src="img/cash.jpg"/>
				</div>
			</div>
		</div>
	</section>

    <footer class="footer bg-dark">
    	<div class="container">
    		<div class="row">
    			<div class="col h-100 text-center text-lg-left my-auto">
    				<p class="text-muted small mb-4 mb-lg-0">&copy; {{ now +  " by Barber Pond Road Self Storage | All Rights Reserved  |  Site by "}} <a href="http://tranzasoftware.com" target="_blank">Tranza Software</a>.</p>
    			</div>
    		</div>
    	</div>
    </footer>

  </div>


</template>

<script>


export default {
  data () {
    return {
      phone: '802-823-7257'
    }
  },
  computed: {
    now: function () {
      let date = new Date()
      return date.getFullYear()
    }
  }
}

</script>
<style scoped lang="scss">
  @import "../assets/styles/main";
</style>
