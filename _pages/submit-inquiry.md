---
layout: page
title: "Submit an Inquiry"
permalink: /submit-inquiry/
---
<div style="padding: 40px;">
<div style="font-size: 20px;">
  <p>Have a question about the journal, our editorial process, or the nature of truth (in academia) itself?   <br><br> Email us at <a href="mailto:qvo.vadis.academia@gmail.com?subject=[INQUIRY]">qvo.vadis.academia@gmail.com</a>, or use the inquiry form below.</p>

<div class="submit-section; style=font-size: 20px;">
  <form action="https://formspree.io/f/mvgqrygk" method="POST" enctype="multipart/form-data">
    <!-- Hidden field to automatically set the subject to "Inquiry Submission" -->
    <input type="hidden" name="_subject" value="[INQUIRY]">
    <!-- Your (Pen)Name Field -->
    <label for="penname">Your (Pen) Name:</label>
    <input type="text" id="penname" name="penname">
    <br><br>
    <!-- Your Email Field -->
    <label for="email">Your Email:</label>
    <input type="email" id="email" name="email">
    <br><br>
    <!-- Private Message to the Editor Field -->
    <label for="message">Your Inquiry:</label>
    <textarea id="message" name="message" rows="5"></textarea>
    <br><br>
    <!-- Attachment Upload Field -->
    <label for="attachment">Attach Any Needed Documents (Word, PDF, JPG, PNG, GIF, Zip):</label>
    <input type="file" id="attachment" name="attachment" accept=".doc,.docx,.pdf,.jpg,.jpeg,.png,.gif,.zip">
    <br><br>
    <!-- Submit Button -->
    <button type="submit">Submit Inquiry</button>
  </form>
</div>

<!-- Success Message -->
<div id="success-message" style="display: none;">
    <p>Your submission has been received. Thank you for submitting your inquiry!</p>
</div>

</div>

</div>