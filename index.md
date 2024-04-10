---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }


{{ site.staffersnobio }}

<!--
{: .success }
**Tip: When working on assignments, use Ctrl+F on this page to search for a keyword and quickly find the relevant lecture. Click the ✏️ emoji to open a static version of the lecture for reference, which is much faster than loading it on DataHub. Also, make sure to use the [reference sheet](https://drive.google.com/file/d/1ky0Np67HS2O4LO913P-ing97SJG0j27n/view?usp=sharing)!**
-->

<!--
{: .success }
>The Final Exam is **this Saturday 3/16 from 7-10PM** in Catalyst 0125 near Plant Power. Join us for a collaborative study session on **Friday 3/15 from 5-8PM** in Solis 104.  
>
>If at least 75% of the class fills out both [SETs](https://academicaffairs.ucsd.edu/Modules/Evals/) and the internal [End-of-Quarter Survey](https://forms.gle/yFoqjCRaBoyFC6nu8), then the entire class will have **1% of extra credit added to their overall grade**. The deadline is Saturday 3/16 at 8AM.
-->

{: .success }
Welcome to DSC 10! To start, read the [syllabus](https://dsc10.com/syllabus) carefully, paying special attention to the ["Getting Started"](https://dsc10.com/syllabus/#-getting-started) section. Make sure to complete the [Welcome Survey](https://forms.gle/4j7t87VWsaJCYbnn8) and [Pretest](https://practice.dsc10.com/pretest/) to get off to a good start!

[Jump to the current week](#week-2-dataframes){: .btn }


{% for module in site.modules %}
{{ module }}
{% endfor %}