---
layout: page2
status: publish
published: true
title: Contact
permalink: /pages/contact/
date: '2017-11-04 12:41:30 -0500'
date_gmt: '2017-11-04 12:41:30 -0500'
categories: []
tags: []
comments: []
---
### CONTACTFORMULIER
{: .offset}

<form class="form-group" role="form" action="https://formspree.io/frank@taalservicelimburg.nl" method="POST">
    <div class="form-group">
        <label for="name">Uw naam (verplicht)</label>
        <input name="name" id="name" placeholder="Naam..." class="form-control" type="text" required>
    </div>
    <div class="form-group">
        <label for="email">Uw e-mailadres (verplicht)</label>
        <input name="email" id="email" placeholder="Email..." class="form-control" type="email" required>
    </div>
    <div class="form-group">
        <label for="subject">Onderwerp</label>
        <input name="subject" id="subject" placeholder="Onderwerp..." class="form-control" type="text" required>
    </div>
    <div class="form-group">
        <label for="message">Uw bericht</label>
        <textarea name="message" id="message" placeholder="Schrijf Uw bericht..." class="form-control" rows="3" cols="20"></textarea>
    </div>
    <div class="form-group">
        <input value="Verstuur bericht!" class="form-control" type="submit">
        <input type="hidden" name="_next" value="/pages/contact/submit/" />
    </div>
    <div>
        <input type="text" name="_gotcha" style="display:none" />
    </div>
</form>

