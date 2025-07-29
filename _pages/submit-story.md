---
layout: page
title: "Tell Your Story Privately"
permalink: /submit-story/
---
<div style="padding: 40px;">
<div style="font-size: 20px;">
  <p>We welcome anonymous or confidential accounts from all those who wish to speak truth to academia.   <br><br>  Share your story by email at <a href="mailto:qvo.vadis.academia@gmail.com?subject=[MEME]">qvo.vadis.academia@gmail.com</a>, or use the form below.</p>

<div class="submit-section; style=font-size: 20px;">
  <form action="https://formspree.io/f/xjkorzka" method="POST" enctype="multipart/form-data">
    <!-- Hidden field to automatically set the subject to "Private Story" -->
    <input type="hidden" name="_subject" value="[STORY]">
    <!-- Your (Pen)Name Field -->
    <label for="penname">Your (Pen) Name:</label>
    <input type="text" id="penname" name="penname">
    <br><br>
    <!-- Your Email Field -->
    <label for="email">Your Email:</label>
    <input type="email" id="email" name="email">
    <br><br>
    <!-- Private Message to the Editor Field -->
    <label for="message">Your Story:</label>
    <textarea id="message" name="message" rows="5"></textarea>
    <br><br>
    <!-- Attachment Upload Field -->
    <label for="attachment">Attach Any Needed Documents (Word, PDF, JPG, PNG, GIF, Zip):</label>
    <input type="file" id="attachment" name="attachment" accept=".doc,.docx,.pdf,.jpg,.jpeg,.png,.gif,.zip">
    <br><br>
    <!-- Submit Button -->
    <button type="submit">Submit</button>
  </form>
</div>

<!-- Success Message -->
<div id="success-message" style="display: none;">
    <p>Your submission has been received. Thank you for sharing your story!</p>
</div>

</div>

</div>