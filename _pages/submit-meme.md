---
layout: page
title: "Submit a Meme"
permalink: /submit-meme/
---
<div style="padding: 40px;">

<div style="font-size: 20px;">
  <p>Sometimes a meme speaks a thousand words.  <br><br> Share your favourite academic memes at <a href="mailto:qvo.vadis.academia@gmail.com?subject=[MEME]">qvo.vadis.academia@gmail.com</a>, or use the meme submission form below.</p>

<div class="submit-section; style=font-size: 20px;">
  <form action="https://formspree.io/f/mrblkdbk" method="POST" enctype="multipart/form-data">
    <!-- Hidden field to automatically set the subject to "Meme Submission" -->
    <input type="hidden" name="_subject" value="[MEME]">
    <!-- Your (Pen)Name Field -->
    <label for="penname">Your (Pen) Name:</label>
    <input type="text" id="penname" name="penname">
    <br><br>
    <!-- Your Email Field -->
    <label for="email">Your Email:</label>
    <input type="email" id="email" name="email">
    <br><br>
    <!-- Private Message to the Editor Field -->
    <label for="message">Background Story:</label>
    <textarea id="message" name="message" rows="5"></textarea>
    <br><br>
    <!-- Attachment Upload Field -->
    <label for="attachment">Attach Your Meme (JPG, PNG, GIF):</label>
    <input type="file" id="attachment" name="attachment" accept=".jpg,.jpeg,.png,.gif">
    <br><br>
    <!-- Submit Button -->
    <button type="submit">Submit Meme</button>
  </form>
</div>

<!-- Success Message -->
<div id="success-message" style="display: none;">
    <p>Your submission has been received. Thank you for submitting your meme!</p>
</div>

</div>

</div>