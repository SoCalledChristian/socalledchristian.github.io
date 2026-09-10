<form action="[https://formspree.io](https://formspree.io/f/mbgjwgka)" method="POST" class="contact-form">
  <div class="form-group">
    <label for="user-name">Your Name:</label>
    <input type="text" id="user-name" name="name" required placeholder="Jane Doe">
  </div>

  <div class="form-group">
    <label for="user-email">Your Email Address:</label>
    <input type="email" id="user-email" name="_replyto" required placeholder="jane@example.com">
  </div>

  <div class="form-group">
    <label for="user-message">Your Message:</label>
    <textarea id="user-message" name="message" rows="5" required placeholder="How can I help you?"></textarea>
  </div>

  <!-- Customizing the Formspree subject line in your inbox -->
  <input type="hidden" name="_subject" value="New Contact Form Submission!">

  <button type="submit">Send Message</button>
</form>
