---
layout: home
title: "AI & Space | Your Name"
---

# Hi, I'm **Your Name**  
AI engineer @ Airbus → 2×MSc → NASA/ESA rover AI → now PhD applicant.

&lt;div align="center"&gt;

| **3 hero numbers** |  |
|---|---|
| 1.3 km | zero-updated rover traverse (Mars Yard) |
| 42 % | slip-prediction gain vs NASA baseline |
| 14 h | open-sourced multi-terrain IMU+stereo data |

&lt;/div&gt;

## Quick links
[CV (pdf)](/cv.pdf) •  
[Google Scholar](https://scholar.google.com/citations?user=YOUR_ID) •  
[GitHub](https://github.com/YOUR_USER) •  
[Email](mailto:you@domain.com)

---

## Projects
{% for p in site.projects %}
### {{ p.title }}  
![thumbnail]({{ p.thumbnail }}){: width="200" }  
{{ p.excerpt }}  
[Details]({{ p.url }}) \| [Code]({{ p.code }}) \| [Paper]({{ p.paper }})
{% endfor %}

---

## Research Vision
Short paragraph (≈120 words) why you want to do a PhD and which labs you target.
