---
permalink: /
# title: "Xiaofeng Mao"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Research Engineer in AI and Roboitcs at Shadow Robot working on dexterous manipulation and co-design. 
I earned my PhD at the University of Edinburgh (advised by Prof. Michael Mistry). 

I aim to enable robots with human-like and even beyond human capability dexterity, agility, and intelligence in contact-rich dexterous manipulation. 



Research Focus
======
My research includes learning from multi-modal information, data-efficient solutions for dexterous long-horizon manipulation and co-design.

- Robot learning of dexterous manipulation with tactile information
- Efficient learning from demonstration with fewer demonstration
- Efficient reinfrocement learning for dexterous long-horizon task with sparse reward setting
- Learning-based robot control in contact-rich settings
- Simulation-to-real transfer for reliable real-world deployment
- Data-efficient and robust policy learning
- Robot learning algorithm and hardware co-design

<!-- Core Abilities
======
- Algorithm design for robotic learning and control
- Reinforcement learning and imitation learning for embodied agents
- Integration of model-based methods with data-driven approaches
- Real-robot experimentation and system-level debugging
- Building end-to-end pipelines from simulation to hardware
- Rapid prototyping, rigorous evaluation, and clear research communication

Current Work Style
======
- Define research hypotheses and measurable success metrics
- Iterate quickly through implementation, evaluation, and ablation
- Convert research prototypes into deployable robotic capabilities
- Collaborate across research and engineering teams to deliver impact -->

Selected Publications
======
{% include base_path %}
{% assign sorted_publications = site.publications | sort: "date" | reverse %}
{% for post in sorted_publications limit: 6 %}
  {% include publication-card.html post=post %}
{% endfor %}

<!-- [View all publications]({{ base_path }}/publications/) -->

<!-- Teaching
======
{% if site.teaching and site.teaching.size > 0 %}
  {% assign sorted_teaching = site.teaching | sort: "date" | reverse %}
  {% for post in sorted_teaching limit: 3 %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

[View all teaching]({{ base_path }}/teaching/) -->
