---
title: "More"
permalink: /more/
author_profile: true
---
## AI Interest Group

At NYU Shanghai, I co-founded the AI Interest Group with Margaret Mao, Yuxuan Xia, and Xinqi Zou. We have successfully held many workshops and seminars in from 2023 to 2024. Yet, I am not actively managing this group anymore. If you are interested, please visit [here](https://github.com/NYUSH-AIIG) and get in touch with the current admin members.

## Vocal Performance

I was a bass singer in NYU Shanghai's *Octave Fusion* A Cappella Choir for 3 years. My vocal range is B1 (which is probably what got me recruited) - D4. Below is my lovely A Cappella family!

<div style="display: flex; gap: 4%;">
    <img src="/images/aca_fall21.jpg" alt="Octave Fusion, Fall 2021" style="flex: 1; min-width: 0; max-width: 48%; border-radius: 8px;" />
    <img src="/images/aca_fall23.jpg" alt="Octave Fusion, Fall 2023" style="flex: 1; min-width: 0; max-width: 48%; border-radius: 8px;" />
</div>

<br>
Check out our previous performances: [Instagram Archive](https://www.instagram.com/octave_fusion/).

## Other Interests

- Bouldering
- Trekking and hiking
- Soccer

## My amazing friends!

I am lucky to be surrounded by many amazing friends, but I'm too lazy to maintain an up-to-date list. In case a friend blames me for forgetting to list them here, I now have an excuse: the random seed is just not on your side.

<p><a href="#" id="random-friend-link"><b>Take me to a random friend →</b></a></p>

<script>
  (function () {
    var friendUrls = [{% for friend in site.data.friends %}"{{ friend.url }}"{% unless forloop.last %}, {% endunless %}{% endfor %}];
    document.getElementById("random-friend-link").addEventListener("click", function (event) {
      event.preventDefault();
      var url = friendUrls[Math.floor(Math.random() * friendUrls.length)];
      window.open(url, "_blank", "noopener");
    });
  })();
</script>
