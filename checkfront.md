---
layout: checkfront
title: Checkfront Droplet
subtitle: Checkfront Demo
icon: fa-calendar-check-o
---

For a technical test, I am to incorporate the Checkfront widget into a website. This is the result of that. I did not make this widget, but it's kind of cool that it works here!

<a href="https://sandcreekad.checkfront.com/reserve/"><button>BOOK NOW!</button></a>

<script type="text/javascript" src="//3glav.checkfront.com/lib/interface--0.js"></script>
<!-- CHECKFRONT BOOKING PLUGIN v25-->
<div id="CHECKFRONT_WIDGET_01"><p id="CHECKFRONT_LOADER" style="background: url('//3glav.checkfront.com/images/loader.gif') left center no-repeat; padding: 5px 5px 5px 20px">Searching Availability...</p></div>
<script>
new DROPLET.Widget ({
host: '3glav.checkfront.com',
target: 'CHECKFRONT_WIDGET_01',
options: 'tabs',
provider: 'droplet'
}).render();
</script>
<noscript><a href="https://3glav.checkfront.com/reserve/" style="font-size: 16px">Continue to Secure Booking System &raquo;</a></noscript>

<script type="text/javascript" src="//sandcreekad.checkfront.com/lib/interface--0.js"></script>
<!-- CHECKFRONT BOOKING PLUGIN v25-->
<div id="CHECKFRONT_WIDGET_02"><p id="CHECKFRONT_LOADER" style="background: url('//sandcreekad.checkfront.com/images/loader.gif') left center no-repeat; padding: 5px 5px 5px 20px">Searching Availability...</p></div>
<script>
new DROPLET.Widget ({
host: 'sandcreekad.checkfront.com',
target: 'CHECKFRONT_WIDGET_02',
provider: 'droplet'
}).render();
</script>
<noscript><a href="https://sandcreekad.checkfront.com/reserve/" style="font-size: 16px">Continue to Secure Booking System &raquo;</a></noscript>
