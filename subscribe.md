---
layout: page
title: Subscribe
permalink: /subscribe/
---
<form action="https://getsimpleform.com/messages?form_api_token=3c24337e8fd79cb593827cd0395d63d2" method="post">
    <li class="contact-li">
        <input type="email" placeholder="Your email" id="email"/>
        <input type="submit" value="Subscribe" id="submit"/>
    </li>
</form>

<form action="https://getsimpleform.com/messages?form_api_token=3c24337e8fd79cb593827cd0395d63d2" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
    <li class="contact-li">
        <input type="email" placeholder="Your email" id="email"/>
        <input type="submit" value="Subscribe" id="submit"/>
    </li>
         
   <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
    <input type="hidden" name='redirect_to' value="/path/to/thank-you.html"/> 
         
</form>
