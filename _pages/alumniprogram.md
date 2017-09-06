---
layout: post
title: Alumni Paddling Program
description: Yearly dues, waivers, and literature.
image: assets/images/outriggers-onwater-mb.jpg
permalink: /alumniprogram/

---
<h2>Alumni Paddling Program</h2>


<p> Pale Kai is happy to announce our new Alumni Paddle Program! Even if your racing days are over, we would like to encourage our long lost ohana to return to the ocean sport they love...no pressure! We are now offering go-outs on Saturday mornings at 9am, led by Gary Prober. </p>	
<p>
If you'd like to join the Alumni Program, please contact Gary.

A hui hou!
</p>
<p>
<strong>Gary Prober</strong><br/>
gprober@yahoo.com</p>
	
<div class="row">
	<div class="6u 12u$(small)">
		<h4>Required Waivers and Literature</h4>
    	{% include alumni-waivers.html %}
	</div>
	<div class="6u$ 12u$(small)">
		<h4>Membership Dues</h4>
		<p>Once dues are paid, you will be added to our TeamSnap for availbility, scheduling, and other fun PKO activities.</p>
		{% for product in site.products %}
		  {% if product.sku == "alumni-member-dues" %}
		  	{% include product.html %}
		  {% endif %}
		{% endfor %}
		
		


	</div>
</div>
	
<!--
<a href="http://www.SignUpGenius.com/go/409044BAFA82CA2F85-20172" class="button">Alumni Paddle Sign-up Genis</a>
-->


