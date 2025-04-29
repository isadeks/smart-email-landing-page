---
title: "Contact Us"
---

### We'd love to hear from you!

If you have any questions, feedback or run into any issues, drop us a line at:

**Email:** [support@yourdomain.com](mailto:support@yourdomain.com)

Or fill out the form below:

<form class="contact-form" action="mailto:{{ .Site.Params.email }}" method="post" enctype="text/plain">
  <label for="name">Name</label>
  <input type="text" name="name" id="name" required>

  <label for="email">Your Email</label>
  <input type="email" name="email" id="email" required>

  <label for="message">Message</label>
  <textarea name="message" id="message" rows="6" required></textarea>

  <button type="submit">Send</button>
</form>
