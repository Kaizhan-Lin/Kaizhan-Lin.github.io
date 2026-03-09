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

I am a postdoctoral researcher in isogeny-based cryptography. My PhD was in Sun Yat-sen University, under the supervision of Binglong Chen and Chang-An Zhao.

My research interest includes isogeny-based and pairing-based cryptography. My google scholar page is available at 
<a href='https://scholar.google.com/citations?user=0ekztlQAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat"></a>

# 📝 Publications 
[9. SQIsign2D^2: New SQIsign2D Variant by Leveraging Power Smooth Isogenies in Dimension One](https://link.springer.com/chapter/10.1007/978-981-95-5113-2_11) <span class="italic">Asiacrypt</span>, 2025.
Zheng Xu, **Kaizhan Lin**, Chang-An Zhao, Yi Ouyang

[8. PIsignHD: A New Structure for the SQIsign Family with Flexible Applicability](https://link.springer.com/chapter/10.1007/978-3-032-10536-3_23)
**Kaizhan Lin**, Weize Wang, Chang-An Zhao, Yunlei Zhao

[7. Pairing Optimizations for Isogeny‐Based Cryptosystems](https://ietresearch.onlinelibrary.wiley.com/doi/abs/10.1049/2024/9631360)
Shiping Cai, **Kaizhan Lin**, Chang-An Zhao

[6. A Faster Software Implementation of SQIsign](https://ieeexplore.ieee.org/abstract/document/10586884)
**Kaizhan Lin**, Weize Wang, Zheng Xu, Chang-An Zhao

[5. Compressed M-SIDH: an instance of compressed SIDH-like schemes with isogenies of highly composite degrees](https://link.springer.com/article/10.1007/s10623-024-01368-z)
**Kaizhan Lin**, Jianming Lin, Shiping Cai, Weize Wang, Chang-An Zhao

[4. Fast subgroup membership testings for G_1, G_2 and G_T on pairing-friendly curves](https://link.springer.com/article/10.1007/s10623-023-01223-7)
Yu Dai, **Kaizhan Lin**, Chang-An Zhao, Zijian Zhou

[3. An alternative approach for computing discrete logarithms in compressed SIDH](https://eprint.iacr.org/2021/1528)
**Kaizhan Lin**, Weize Wang, Lin Wang, Chang-An Zhao

[2. Faster Public-Key Compression of SIDH With Less Memory](https://ieeexplore.ieee.org/abstract/document/10076822)
**Kaizhan Lin**, Jianming Lin, Weize Wang, Chang-An Zhao

[1. Faster Key Generation of Supersingular Isogeny Diffie-Hellman](https://globals.ieice.org/en_transactions/fundamentals/10.1587/transfun.2022EAP1026/_p)
**Kaizhan Lin**, Fangguo Zhang, Chang-An Zhao

# 📖 Educations
- *2020.09 - 2025.06*, Ph.D. degree in mathematics, School of Mathematics, Sun Yat-sen University. 
- *2016.08 - 2020.06*, B.S. degree in mathematics, School of Mathematics, Sun Yat-sen University.

# 💬 Invited Talks
- *2025.09*, Leuven Isogeny Days 6, SQIsign2D2: New SQIsign2D Variant by Leveraging Power Smooth Isogenies in Dimension One.
