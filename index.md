---
layout: default
title: user@home:~$
---

<img src="https://via.placeholder.com/150" class="profile-img" alt="My Photo">

### About Me

I am Huanbin Teng (滕焕斌) <span style="font-family: 'Charis SIL', 'Times New Roman', serif; font-size: 1.2em; color: #b03030;">[tʰəŋ˧˥ xwan˥˩ pin˥]</span>.

<!-- Spectrogram Image Placeholder -->

<figure style="border: 2px solid #3d545e; padding: 5px; background: #fff; margin-bottom: 20px;">
<img src="" alt="Wideband spectrogram of the name Teng Huanbin" style="width: 100%; border: none;">
<figcaption style="font-size: 0.9em; color: #666; font-style: italic; text-align: center; margin-top: 5px;">
Fig 1. Wideband spectrogram of my name utterance (Praat 6.0).
</figcaption>
</figure>

I am currently a student of Linguistics at [Insert University Name], standing at the fascinating intersection of Sociology and Computational Linguistics.

My academic journey is defined by a dual obsession with structure—the invisible architectures that govern our reality. I am as captivated by the macro-level hierarchies of social organization as I am by the micro-level recursions of syntactic trees and the acoustic patterns of speech.

Unlike traditional qualitative approaches, I prefer to decode these structures through a computational lens. Whether I am analyzing the spectral tilt of breathy vowels or modeling social network dynamics, my goal is to quantify the abstract.

### Research Interest
* Language Variation and Change
* Computational Linguistics
* Quantitative Methods

---

### Blogs
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <span style="color: #666;">{{ post.date | date: "%Y-%m-%d" }}</span>
      » <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
