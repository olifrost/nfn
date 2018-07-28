---
layout: page
title: "What is Nice Fake News?"
permalink: /mission.html
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

*Fake news has torn our world apart, so now fake news must mend it.*


<div class="youtube-player">
<iframe src="https://www.youtube.com/embed/{{ site.video }}?rel=0&amp;modestbranding=1;" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>




NFN is a <a href="/">Nice Fake News site</a>.

It publishes lies that create smiles, crush fears, or inspire you to donate your kidneys.

Stories are promoted on Facebook <a href="{{ "/donate " | relative_url }}">with overseas donations</a>, and <a href="{{ "/joinus" | relative_url }}">seeded by Russian hackers</a>.

![Nice Fake News](/img/NFN6.jpg)

Our demands are simple.

We are giving news organisations <strong id="thecountdown"></strong> to publish a real inspiring story on their front page.

Else we will promote another fake one.


Until then, share an article and spread some niceness.

Yours,  
<a href="http://olifro.st" class="russian">Оли Фрост</a>  
The Nice Russian Hacker

Go to <a href="/faq/">FAQ</a>


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
