---
layout: page
title: Contact
permalink: /contact
comments: false
---

<form   action="https://formspree.io/f/mdojawek" method="POST">    
<p class="mb-4">Bitte sende Deine Nachricht an {{site.name}}. Wir antworten so schnell wie möglich!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Addresse*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Nachricht*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Senden">
</form>