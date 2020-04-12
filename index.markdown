---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div id="atf">
	<div>
		<h1 id="main-title">product surgery<span class="tertiary-color transitioning-period period-1">.</span></h1>
		<div id="key-messaging-container">
			<p class="key-messaging">Finding product-market fit is hard.</p>
			<p class="key-messaging">Get free, expert advice at our virtual surgeries.</p>
		</div>
		{% include button.html url="https://sglondon.typeform.com/to/M4bNXE" %}
	</div>
</div>

<div id="experts-container">
	<div id="experts-header"><h3>Joined by experts from</h3></div>
	<img id="index" src="/assets/images/index_ventures_colourised.png" alt="Index Ventures">
	<img id="stride" src="/assets/images/stride_vc_colourised.png" alt="Stride.VC">	
	<img id="forward" src="/assets/images/forward_partners_colourised.png" alt="Forward Partners">	
	<img id="clearscore" src="/assets/images/clearscore_colourised.png" alt="ClearScore">			
</div>

<div id="next-up-container">
	<div id="next-up-header"><h2>next up<span class="primary-color">.</span></h2></div>
	<div id="next-up">
		<img id="fred" src="/assets/images/fred-destin.jpg" alt="Fred Destin">
		<div class="profile">
			<p class="date">23rd April 2020</p>
			<p class="name">Fred Destin, Partner at Stride.VC</p>
			<p>Fred is the founder of Stride.VC; a seed-stage fund operating in London and Paris. Previously he was a General Partner at Accel, and an early backer in notable startups including Deliveroo, Zoopla, Secret Escapes, and CarWow.</p>
		</div>
	</div>
</div>


<div id="previously-container">
	<div id="previously-header"><h2>previously<span class="secondary-color">.</span></h2></div>
	<div class="previously">
		<img id="dharmesh" src="/assets/images/fred-destin.jpg" alt="Fred Destin">
		<div class="profile">
			<p class="date">23rd April 2020</p>
			<p class="name">Fred Destin, Partner at Stride.VC</p>
			<p>Fred is the founder of Stride.VC; a seed-stage fund operating in London and Paris. Previously he was a General Partner at Accel, and an early backer in notable startups including Deliveroo, Zoopla, Secret Escapes, and CarWow.</p>
		</div>
	</div>
</div>

<div id="quote-container">
	<div id="quotes-header"><h3>Feedback from startups</h3></div>
	<div id="quote-1" class="quote">
		<p>It was incredible value, and a safe space for feedback. I'd pay for this.</p>
	</div>
	<div id="quote-2" class="quote">
		<p>I found the session super useful. I'll keep you guys posted on progress.</p>
	</div>
	<div id="quote-3" class="quote">
		<p>We really enjoyed it, your feedback was very actionable.</p>
	</div>
</div>

<h2>how it works<span class="tertiary-color">.</span></h2>
<p> Private, one-on-one sessions </p>

<h2>you<span class="primary-color">.</span></h2>
<p> You're a startup with a live product. </p>

<h2>us<span class="secondary-color">.</span></h2>
<p> We're the team that established Startup Grind London.</p>

<script>
	document.addEventListener('DOMContentLoaded', function() {
	    var elems = document.getElementsByClassName("transitioning-period");
		setInterval(function(){
		    if(elems[0].classList.contains("period-1")) {
		        elems[0].classList.remove("tertiary-color");
	    		elems[0].classList.add("primary-color");
		        elems[0].classList.remove("period-1");
	    		elems[0].classList.add("period-2");
		    } else if(elems[0].classList.contains("period-2")) {
		        elems[0].classList.remove("primary-color");
	    		elems[0].classList.add("tertiary-color");
		        elems[0].classList.remove("period-2");
	    		elems[0].classList.add("period-3");
		    } else if(elems[0].classList.contains("period-3")) {
		        elems[0].classList.remove("tertiary-color");
	    		elems[0].classList.add("secondary-color");
		        elems[0].classList.remove("period-3");
	    		elems[0].classList.add("period-4");	    		
		    } else if(elems[0].classList.contains("period-4")) {
		        elems[0].classList.remove("secondary-color");
	    		elems[0].classList.add("tertiary-color");
	    		elems[0].classList.remove("period-4");
	    		elems[0].classList.add("period-1");	
		    }	    	    
		}, 5000);
	}, false);

</script>