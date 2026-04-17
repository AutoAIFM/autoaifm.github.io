---
title: "AutoAI-FM: AutoAI meets Foundation Models"
layout: single
header:
  overlay_image: /jahanzeb-ahsan-NVNOy_DkvXA-unsplash.jpg
  overlay_filter: 0.5
sidebar: null
---

Automated artificial intelligence (AutoAI) comprises meta-algorithmic methods that improve performance by, for example, automatically selecting, configuring, designing or explaining AI algorithms for a given task or problem distribution. Its central motivation is the limited generality of algorithms: no single method performs optimally across all problems, and in practice algorithmic performance varies substantially across tasks and instances. Over the past two decades, AutoAI has delivered state-of-the-art results across diverse domains, including NP-complete problem solving, black-box optimisation, and machine learning.

In recent years, large language models (LLMs) and other foundation models have emerged as powerful general-purpose tools, enabling strong performance on a wide range of tasks and reviving the notion of a single, universal solver. These models are increasingly being applied to machine learning, optimisation, planning, constraint solving, and other traditional AutoAI application areas.

Although these research lines can appear to compete, recent work has shown that combining AutoAI with LLMs and other foundation models is often essential to unlocking their full potential, yielding systematic gains over either paradigm alone. While traditional AutoAI methods heavily rely on empirical performance data, often collected for the specific task distribution at hand, LLMs encode broad world knowledge acquired during large-scale pretraining, and can leverage previous knowledge of effectively solving other, related problems to enhance the performance of the optimisation process. Moreover, LLMs are capable of in-context learning, a mechanism that has proven highly effective in small-data regimes, including structured tabular settings as demonstrated by recent tabular foundation models. This ability enables rapid and efficient updates in precisely the data settings that underpin many AutoAI frameworks.

On the other hand, foundation models are not universal solvers; instead, they excel at specific tasks and introduce a new set of challenges and limitations that give rise to novel application scenarios and create the need for specialized AutoAI methods. For example, AutoAI methodologies can be applied to improve pretraining, post-training, fine-tuning, distillation, prompt tuning, LLM selection (also known as routing), or the configuration of entire agentic systems. Moreover, while LLMs have shown great capabilities, they are still vulnerable to hallucinations and adversarial attacks. As such, applying AutoAI to optimise them for not only pure performance, but also reducing safety risks is a promising field of research.

This workshop aims to deepen the investigation of research topics at this intersection by fostering discussion on approaches that integrate AutoAI methods with LLMs and foundation models.

**Submission deadline:** 4 May 2026 (AoE)  
**Notification:** 11 June 2026 (AoE)  
**Workshop dates:** 15, 16 or 17 August 2026 (TBD)  
**Location:** Bremen, Germany  
**Collocated with:** [IJCAI-ECAI 2026](https://ijcai-ecai2026.org/)

Please see the [Call for Papers](/cfp/).

## Keynote Speakers

{% for speaker in site.data.autoai_fm.speakers %}
- **{{ speaker.name }}** ({{ speaker.affiliation }})
{% endfor %}

## Organisers

<div style="display: flex; flex-wrap: wrap; justify-content: flex-start; gap: 30px; margin-top: 20px;">
  {% for organizer in site.data.autoai_fm.organizers %}
  <div style="text-align: center; width: 150px;">
    {% if organizer.image %}
    <img src="{{ organizer.image }}" alt="{{ organizer.name }}" style="width: 150px; height: 150px; border-radius: 50%; object-fit: cover; margin-bottom: 10px;">
    {% else %}
    <div style="width: 150px; height: 150px; border-radius: 50%; background-color: #ddd; line-height: 150px; color: #888; margin: 0 auto 10px auto;">No Image</div>
    {% endif %}
    <p style="margin: 0; line-height: 1.2;"><strong>{{ organizer.name }}</strong></p>
    <p style="margin: 5px 0 0 0; font-size: 0.85em; line-height: 1.2;">{{ organizer.affiliation }}</p>
    <p style="margin: 5px 0 0 0; font-size: 0.8em;"><a href="{{ organizer.website }}" target="_blank">Website</a></p>
  </div>
  {% endfor %}
</div>

Contact: [autoaifm@aim.rwth-aachen.de](mailto:autoaifm@aim.rwth-aachen.de)
