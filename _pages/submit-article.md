---
layout: page
title: "Submit an Article"
permalink: /submit-article/
---
<div style="padding: 40px;">
<div style="font-size: 20px;">
  <p>Interested in publishing in QVO·VADIS·ACADEMIA?  <br><br> Please send your most incisive, scholarly, or satirical work at <a href="mailto:qvo.vadis.academia@gmail.com?subject=[ARTICLE]">qvo.vadis.academia@gmail.com</a>, or use the article submission form below.</p>

<div class="submit-section; style=font-size: 20px;">
  <form action="https://formspree.io/f/xnnzvrqb" method="POST" enctype="multipart/form-data">
    <!-- Hidden field to automatically set the subject to "Article Submission" -->
    <input type="hidden" name="_subject" value="[ARTICLE]">
    <!-- Your (Pen)Name Field -->
    <label for="penname">Your (Pen) Name:</label>
    <input type="text" id="penname" name="penname">
    <br><br>
    <!-- Your Email Field -->
    <label for="email">Your Email:</label>
    <input type="email" id="email" name="email">
    <br><br>
    <!-- Private Message to the Editor Field -->
    <label for="message">Private Message to the Editor:</label>
    <textarea id="message" name="message" rows="5"></textarea>
    <br><br>
    <!-- Attachment Upload Field -->
    <label for="attachment">Attach Your Document (Word, PDF, Tex, Zip):</label>
    <input type="file" id="attachment" name="attachment" accept=".doc,.docx,.pdf,.tex,.jpg,.jpeg,.png,.gif,.zip">
    <br><br>
    <!-- Submit Button -->
    <button type="submit">Submit Article</button>
  </form>
</div>

<!-- Success Message -->
<div id="success-message" style="display: none;">
    <p>Your submission has been received. Thank you for submitting your article!</p>
</div>

</div>

</div>