---
layout: page
title: Martin's Dog Farm | Adoption Form
description:
sitemap:
priority: 0.001
lastmod: 2018-26-04
changefreq: weekly
---
<!-- Main -->
<h1>Adoption Form <img class="MDF_logo pull-right application" src='{{ "/images/MDF_logo.jpg" | absolute_url }}'>
</h1>
<form method="POST" action="https://formspree.io/{{site.email}}" id="MDF_form">
    <div class="field">
        <label for="name">Name</label>
        <input type="text" name="name" id="name" />
    </div>
    <div class="field">
        <label for="street_address">Street Address</label>
        <input type="text" name="street_address" id="street_address" />
    </div>
    <div class="field section">
        <div class="col">
            <label for="city">City</label>
            <input type="text" name="city" id="city" />
        </div>
        <div class="col">
            <label for="state">State</label>
            <input type="text" name="state" id="state" />
        </div>
        <div class="col">
            <label for="zip">Zip Code</label>
            <input type="text" name="zip" id="zip" />
        </div>
    </div>
    <div  class="field section">
        <div class="col">
            <label for="home_phone">Home Phone</label>
            <input type="text" name="home_phone" id="home_phone" />
        </div>
        <div class="col">
            <label for="work_phone">Work Phone</label>
            <input type="text" name="work_phone" id="work_phone" />
        </div>
        <div class="col">
            <label for="cell_phone">Cell Phone</label>
            <input type="text" name="cell_phone" id="cell_phone" />
        </div>
    </div>
    <div class="field">
        <label for="_replyto">Email</label>
        <input type="text" name="_replyto" id="_replyto" />
    </div>
    <div class="field">
        <label for="dog">Which canine you are interested in adopting?</label>
        <input type="text" name="dog" id="dog"/>
    </div>
    <div class="field">
        <label for="dog_id">ID Number if known</label>
        <input type="text" name="dog_id" id="dog_id"/>
    </div>
    <div class="field">
        <label for="gender">Gender of dog?</label>
        <input type="radio" name="gender" value="male"> Male
        <input type="radio" name="gender" value="female"> Female
    </div>
    <div class="field">
        <label for="other_animals">Please list other pet(s) in your home. Specify age and species (dog, cat, etc.):</label>
        <textarea name="other_animals" id="other_animals" rows="3"></textarea>
    </div>
    <div class="field">
        <label for="surrender">Have you ever had to surrender a pet? (If yes, please explain)</label>
        <input type="radio" name="surrender" value="yes"> Yes
        <input type="radio" name="surrender" value="no"> No
        <textarea name="surrender_text" id="surrender_text" rows="3"></textarea>
    </div>
    <div class="field">
        <label for="home">Do you own or rent your current home?</label>
        <input type="radio" name="home" value="home"> Home
        <input type="radio" name="home" value="rent"> Rent
        <input type="radio" name="home" value="other"> Other
    </div>
    <div class="field">
        <label for="how_long">How long have you lived there?</label>
        <input type="text" name="how_long" id="how_long"/>
    </div>
    <div class="field">
        <label for="move">Do you own or rent your current home?</label>
        <input type="radio" name="move" value="yes"> Yes
        <input type="radio" name="move" value="no"> No
        <input type="radio" name="move" value="maybe"> Maybe
    </div>
    <div class="field">
        <label for="message">Message</label>
        <textarea name="message" id="message" rows="3"></textarea>
    </div>
    <ul class="actions">
        <li><input type="submit" value="Send Application" /></li>
    </ul>
</form>