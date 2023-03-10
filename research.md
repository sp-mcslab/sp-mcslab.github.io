---
title: Research Themes
feature_text: |
  ## Research

feature_image: "/assets/uploads/bg_5_r2.jpg"
excerpt: "A demo of Markdown and HTML includes"
aside: false
---

* * *


### Automotive Cybersecurity

* **Motivation**: Connected-Car Hacking and Fatal Crash in Driving Automatgion
  * Jeep Chrokee Hacked (by C. Miller and C. Valasek, at Black hat 2015)
  > Automotive hack paradigm changed: via wireless network, unspecified targets, direct to safety, determined of manufactures responsibilities
  * Autopilot Accident (Florida, May 2016)
{% include figure.html image="/assets/uploads/Research_motivation_CC-Hack_crop.png" caption="Motivation: Connected-Car Hacking" width="600" %}
{% include figure.html image="/assets/uploads/Research_motivation_Crash-AV_crop.png" caption="Motivation: Fatal Crash in Driving Automation" width="600" %}

* **Plug and charge and ISO 15118**
  * [Research #2: PnC](#research-projects)

* **Cybersecurity management system, UN R.155 and ISO/SAE 21434**
  * Law and regulation trends in automobiles require reinforcement of security as well as safety

{% include figure.html image="/assets/uploads/Research_Regulations_crop.png" caption="Automotive Regulations for Safety and Security" width="600" %}

* **TARA and PIER method for cybersecurity risk assessment**
  * [Research #1: TARA & PIER](#research-projects)

* **In-Vehicle IDS and Remote Analysis**
  * Automotive Intrusion Detection Research of message and States Learning In-Vehicle Network
  * NotClassifying data that will not be used based on the Hierarchical Multi-Class Model
{% include figure.html image="/assets/uploads/Research_IDS1_crop.png" caption="Intrusion Detection for In-Vehicle Network" width="600" %}
{% include figure.html image="/assets/uploads/Research_IDS2_crop.png" caption="Hierarchical Multi-labeled Hierarchical Classification Method for Intrusion Detection" width="600" %}

* **Automotive OTA software update**
  * Integrity validation of ECU software to prevent manipulated code injection attacks
{% include figure.html image="/assets/uploads/Research_AutomotiveOTA_crop.png" caption="Automotive Software Update Over-The-Air (OTA)" width="600" %}

* **Auto-ISAC council**
  * Enhancing cybersecurity and sharing information on cyber threats and vulnerabilities among the automobile industrial members and US Governments since 2015
  > Auto-ISAC aims to promote collaboration and coordination among its members, such as vehicle manufacturers, suppliers, and automotive cybersecurity professionals
{% include figure.html image="/assets/uploads/Research_AutoISAC_crop.png" caption="Automotive Software Update Over-The-Air (OTA)" width="600" %}

### Research Projects
* **Research on Automotive Cybersecurity Threat Analysis and Risk Assessment Methodology** (2021.9~2022.8, Hansung University)
  * Risk assessment from cyber threats, vulnerabilities, likelihood, and damages on target vehicles
  > The PIER approach, which considers cyber-resilience, covers not only the risk factors of probability and impact, but also exposure and recovery
{% include figure.html image="/assets/uploads/Research_TARA_PIER_crop.png" caption="PIER method for TARA" width="600" %}

* **Research on Security Authentication Technology for Automatic Charging and Payment of Electric Vehicles** (2022.9~2024.2, Hansung University)
  * Authorization for EV charging and automatic payment based on ISO 15118 using PKI and X.509
{% include figure.html image="/assets/uploads/Research_PnC_crop.png" caption="PnC based on ISO 15118" width="600" %}

* **Research on Moving Objects Recognition Technology for Autonomous Driving Collision Avoidance Control** (2022.9~2024.2, Hansung University)
  * Prediction of movement and interference of moving objects in the driving trajectory
{% include figure.html image="/assets/uploads/Research_CollisionAvoidance_crop.png" caption="Collision Avoidance for Autonomous Driving" width="600" %}

* **Modeling Research for Multi-link Operation of Wi-Fi 7** (2022.9~2024.2, Hansung University)

<!--
[A link](https://david.darn.es "A link")

Lorem ipsum dolor sit amet, consectetur adip* isicing elit, sed do eiusmod *tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in [A link](https://david.darn.es "A link") reprehenderit in voluptate velit esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `some code` est laborum.

* An item
* An item
* An item
* An item
* An item

1. Item one
2. Item two
3. Item three
4. Item four
5. Item five

> A simple blockquote

Some HTML...

``` html
<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>
```

...CSS...

``` css
blockquote {
  text-align: center;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
```

...and JavaScript

``` js
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
```

`Single line of code`

## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="https://david.darn.es" %}

{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://david.darn.es" %}
{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes){% endraw %}
```

### Video include

{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}

``` html
{% raw %}{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}{% endraw %}
```
-->
