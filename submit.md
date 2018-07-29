---
layout: page
title: Submit
permalink: /submit.html
description: Have a tip? Submit a Nice Fake News story to our editors
---

<style>
article {
    font-size: 1.3em;

}
.full-width {
  background-color: #0c0c0c;
  color: white;
}

textarea, input {
  color: white;
  font-size: 1.6rem;
}

header {
  border-bottom: 3px solid #BE0712;
}


</style>

*Have a tip? Submit a Nice Fake News story to our editors.*

<form action="https://formspree.io/mail@olifro.st" method="POST">

  <label for="Message">What's the story?</label>
  <textarea type="text" name="description" rows="20" cols="20" id="Message" placeholder="Your story" required></textarea>

  <label for="Email">Contact (Optional):</label>
  <input type="email" name="replyto"  id="Email" placeholder="So we can credit you">
<input type="hidden" name="_next" value="http://nicenews.live/thanks" />
    <input type="submit" value="Submit" class="submit-button">
</form>
