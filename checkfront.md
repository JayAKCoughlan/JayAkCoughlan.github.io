---
layout: checkfront
title: Checkfront Droplet
subtitle: Checkfront Demo
icon: fa-calendar-check-o
---

For a technical test, I am to incorporate the Checkfront widget into a website. This is the result of that. I did not make this widget, but it's kind of cool that it works here!

<script type="text/javascript" src="//jayscodingbeta.checkfront.com/lib/interface--0.js"></script>
<!-- CHECKFRONT BOOKING PLUGIN v25-->
<div id="CHECKFRONT_WIDGET_01"><p id="CHECKFRONT_LOADER" style="background: url('//jayscodingbeta.checkfront.com/images/loader.gif') left center no-repeat; padding: 5px 5px 5px 20px">Searching Availability...</p></div>
<script>
new DROPLET.Widget ({
host: 'jayscodingbeta.checkfront.com',
target: 'CHECKFRONT_WIDGET_01',
tid: 'hide',
popup: '63',
options: 'tabs',
provider: 'droplet'
}).render();
</script>
<noscript><a href="https://jayscodingbeta.checkfront.com/reserve/" style="font-size: 16px">Continue to Secure Booking System &raquo;</a></noscript>