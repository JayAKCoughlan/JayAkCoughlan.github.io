---
layout: checkfront
title: Checkfront Droplet
subtitle: Checkfront Demo
icon: fa-calendar-check-o
---

For a technical test, I am to incorporate the Checkfront widget into a website. This is the result of that. I did not make this widget, but it's kind of cool that it works here!

<div class="cf-droplet">
    <script type="text/javascript" src="//tiltpinball.checkfront.com/lib/interface--0.js"></script>
    <!-- CHECKFRONT BOOKING PLUGIN v25-->
    <div id="CHECKFRONT_WIDGET_01"><p id="CHECKFRONT_LOADER" style="background: url('//tiltpinball.checkfront.com/images/loader.gif') left center no-repeat; padding: 5px 5px 5px 20px">Searching Availability...</p></div>
    <script>
        new DROPLET.Widget ({
        host: 'tiltpinball.checkfront.com',
        target: 'CHECKFRONT_WIDGET_01',
        provider: 'droplet'
        }).render();
    </script>
    <noscript><a href="https://tiltpinball.checkfront.com/reserve/" style="font-size: 16px">Continue to Secure Booking System &raquo;</a></noscript>
</div>