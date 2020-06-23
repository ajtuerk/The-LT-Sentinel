---
title: "Contact"
permalink: "/contact.html"
---

<div class="contact-wrap>
  <div class="about-us">
    The LT-Sentinel is an online news site started in June 2020. You can check out our authors <a href="/authors-list.html">here</a>.
  </div>
  <div class="mission">
  Our mission at the LT-Sentinel is to provide you with up to date stories that keep you in the loop on everything from sports to politics. We take pride in our journalistic approach and our stories are backed with the utmost authenticity and dedication from our writers.
  </div>
</div>
  

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>
