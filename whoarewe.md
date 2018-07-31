---
layout: page
title: "We Are Anonynice"
permalink: /whoarewe.html
description:  "A group of Russian hackers who spread nice fake news."
image: /img/nfn-1.jpg
---

<style>
article {
    font-size: 1.3em;

}
hr {
  border-color: #BE0712;
}
.content {
  min-width: 100%;
}
.full-width {
  background-color: #0c0c0c;
  color: white;

}
header {
  border-bottom: 3px solid #BE0712;
}

h1 {

  font-weight: 500;
  letter-spacing: -0.1;
}

a {
  color: #BE0712;
}

/*article img {
  border: 1px solid white;
}*/

</style>

A group of Russian hackers who spread <a href="/">nice fake news</a>.

From developing bot networks, to hi-jacking verified accounts.

We will use whatever means is necessary.

<div class="youtube-player">
<iframe src="https://www.youtube.com/embed/{{ site.video }}?rel=0&amp;modestbranding=1;" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

Stories are first published to Nice Fake News site (NFN)

We then promote them on your corrupt social networks <a href="{{ "/donate " | relative_url }}">using offshore financing</a>.

And further spread them by our <a href="{{ "/joinus" | relative_url }}">hacker network</a>.

![Nice Fake News](/img/NFN6.jpg)



Our demands are simple.

We are giving news organisations <strong id="thecountdown"></strong> to publish a real inspiring story on their front page.

Else we will promote another fake one.

![](/img/NFN4.jpg)

Until then, share an article and spread some niceness.

Yours,
<a href="http://olifro.st" class="russian">Оли Фрост</a>  
The Friendly Russian Hacker

 [>> Go to NFN (Nice Fake News)](/)


![Nice Fake News](/img/NFN3.jpg)


<script type="text/javascript">

var countDownDate = new Date("Jun 11, 2018 09:00:00").getTime();


var x = setInterval(function() {


  var now = new Date().getTime();


  var distance = countDownDate - now;


  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);


  document.getElementById("thecountdown").innerHTML =  hours + ":"
  + minutes + ":" + seconds;


  if (distance < 0) {
    clearInterval(x);
    document.getElementById("thecountdown").innerHTML = "24 hours";
  }
}, 1000);
</script>
