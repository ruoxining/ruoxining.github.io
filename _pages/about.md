---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi everyone! My name is Ruoxi Ning [宁若汐]. I am a first-year Ph.D. candidate at <a href='https://uwaterloo.ca/'>UWaterloo</a>, supervised by <a href='https://uwaterloo.ca/computer-science/about/people/fhs'>Freda Shi</a>. 

During my undergraduate years in <a href='https://www.zju.edu.cn/english/'>Zhejiang University</a>, I pursued a double major in English linguistics and computer science. I worked as an intern at <a href='https://westlakenlp.netlify.app/'>WestlakeNLP</a> with <a href='https://frcchang.github.io/'>Prof. Yue Zhang</a> (2021. June - now). I have also been visiting <a href='https://statnlp-research.github.io/'>StatNLP</a> with <a href='https://istd.sutd.edu.sg/people/faculty/lu-wei'>Prof. Wei Lu</a> (2023. June - 2023. Oct).

I am recently reading and discussing to decide my directions and welcoming a wide range of ideas to work on. Generally, my interests fall in the following topics:

- **Interpretability**: How do (multimodality) models perform next-word prediction and how do they express their knowledge through this? If treating (multimodality) language models as a human learning everything through vision, language, and audio, they assemble each other very much, and thus abundant linguistic or cognitive science rules should apply to models as well, e.g., the multilingual transfer effect, and Chomsky's hierarchy. We hope to analyze the model's decoding algorithm through methods inspired by these theories and make explanations for model behaviors.

- **Computational Linguistics / Cognitive Science**: How can we adopt language models in investigating linguistics and cognitive science questions that cannot be solved by traditional methods? When we wonder how languages got involved in possessing features (e.g., grammar, number systems, color systems), or how the signifier, signified, and meaning are perceived by us, it is impossible for us to either observe the creation of a language or open the brain🧠 to see everything (at least we cannot do this every time :\) ). However, it is possible for us to simulate all these situations through language models.

 
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 📣 News

- *2024.09*: Recieved [Cohere Graduate Scholarship](https://uwaterloo.ca/current-graduate-students/catalogs/graduate-funding-and-awards-database/cohere-graduate-scholarship-computer-science) awarded by CohereAI and University of Waterloo. Thank you all for recognizing me :D

- *2024.08*: I will be participating ACL2024 @Bangkok, looking forward to connecting / chatting with you all!

- *2024.04*: I will be an incoming Ph.D. candidate to university of Waterloo, co-supervised by [Freda Shi](https://uwaterloo.ca/computer-science/about/people/fhs) and [Olga Veksler](https://cs.uwaterloo.ca/~oveksler/).


# 📝 Publications 
<a href='https://scholar.google.com/citations?user=C_WZIIYAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/novelQA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[NovelQA: A Benchmark for Long-Range Novel Question Answering](https://arxiv.org/pdf/2403.12766)

Cunxiang Wang*, **Ruoxi Ning\***, Boqi Pan, Tonghui Wu, Qipeng Guo, Cheng Deng, Guangsheng Bao, Qian Wang, Yue Zhang.

[**NovelQA Online Testbench**](https://www.codabench.org/competitions/2295/#/pages-tab) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> We welcome submissions to run test on our benchmark!
</div>
</div>

<!-- simple paper -->

- `EMNLP 2024 Demo` [TAIL: A Toolkit for Automatic and Realistic Long-Context Large Language Model Evaluation](https://aclanthology.org/2024.emnlp-demo.21/). Gefei Gu, Yilun Zhao, **Ruoxi Ning**, Yanan Zheng, Arman Cohan.

<!-- 
- `Under Review` A Quantitative Study of Register Differentiation and Change in Contemporary English: Latinate/Germanic Ratio as a Parameter. **Ruoxi Ning**, Fanke Zeng, Bin Shao. -->

- `Preprint` [GLoRE: Evaluating Logical Reasoning of Large Language Models](https://arxiv.org/pdf/2310.09107). Hanmeng Liu, Zhiyang Teng, **Ruoxi Ning**, Jian Liu, Qiji Zhou, Yue Zhang.

- `ACL 2022 Findings` [Challenges to open-domain constituency parsing](https://aclanthology.org/2022.findings-acl.11.pdf). Sen Yang, Leyang Cui, **Ruoxi Ning**, Di Wu, Yue Zhang.

<!-- # 🎖 Honors and Awards
- *2024.09*: Recieved [Cohere Graduate Scholarship](https://uwaterloo.ca/current-graduate-students/catalogs/graduate-funding-and-awards-database/cohere-graduate-scholarship-computer-science) awarded by CohereAI and University of Waterloo. Thank you all for recognizing me :D
-->

# 📖 Educations
- *2024.09 - 2029.06(expected)*, <a href='https://www.zju.edu.cn/english/'>University of Waterloo</a>, <a href='https://cs.uwaterloo.ca/'>David R. Cheriton School of Computer Science</a>, Ph.D. candidate.

- *2019.09 - 2024.07*, <a href='https://www.zju.edu.cn/english/'>Zhejiang University</a>. I received a double major (English Linguistics & Computer Science). A double major means that I am completing core courses required by a CS double degree except a dissertation in CS, e.g. ADS, OS, TCS. Besides, though the CS double-X does not require any AI courses, I still finished many of them e.g., ML, NLP, DS. For research, I worked with <a href='https://person.zju.edu.cn/en/shaobin'>Bin Shao</a> from School of International Studies on finding the relevance between word origins and text formality in English language.

- *2016.09 - 2019.06*, <a href='https://en.wikipedia.org/wiki/Jinan_Foreign_Language_School'>Jinan Foreign Language School</a>: I was an English-language-guaranteed student from JFLS (exempting Chinese Gaokao). My continuous interest in STEM subjects and my previous experience in winning a 1st Prize in National Olympiad in Informatics in Provinces (NOIP2015, junior group) have driven me to explore and take a double major in Computer Science, which further nurtured my passion for Natual Language Processing (NLP) and Computational Linguistics (CL).

# 💬 Invited Talks
- *2022.10*, I gave a presentation on Philosophy of Linguistics at WestlakeNLP. Many thanks to <a href='https://dnaihao.github.io/research.html'>Naihao Deng</a> for arranging this meeting!

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
  
# 🧑‍🏫 Teaching
- *2024.09 - 2024.12*, Teaching Assistant, CS486/686 Introduction to Artificail Intelligence (Fall 2024).

# 🎹 Interesting Facts!
- I have a blog <a href='https://ruoxining.github.io/notebook'>🏛️ Mini Babel Library</a> written mostly in Chinese Mandarin. I believe that taking notes is a good way forcing one to digest the knowledge duing learning and reinforce the understanding. Welcome to explore my notes in CS, AI, linguistics, and life skills here!
  
- I am a foreign language learner. Besides Chinese and English, I can also use French (~B1) and German (~A1) and I am eagerly learning them. My wish is to reach at least B2 in these two languages before graduation. Be my Duolingo friend at [minervaning](https://www.duolingo.com/profile/minervaning).

- I enjoy reading philosophy, linguistics, and classics. I am also a big fan of German and Austrian musicals and classical music, especially the works of Richard Wargner, Edward Grieg, Sergei Rachmaninoff, Richard Strauss, and Philip Glass. 🎵


<!-- - interactive page -->
<!-- - My interactive page is at [Interactive webpage](ruoxining.github.io/subpages/interactUI) -->
<!-- - portfolio -->
<!-- - I used to be a part-time graphic designer and this is my [Portfolio](ruoxining.github.io/subpages/portfolio). My designs tries to combine simple forms with philosophical implicatures. -->