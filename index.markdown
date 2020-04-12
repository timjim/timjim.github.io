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

<div id="quote-container">
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

## next up

Fred Destin
Partner at Stride.VC
(ex-Accel, ex-board at Deliveroo, Zoopla)



## previously

## how it works

## you

## us

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