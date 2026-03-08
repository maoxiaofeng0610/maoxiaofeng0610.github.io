---
permalink: /
# title: "Xiaofeng Mao"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Research Engineer in AI and Robotics at Shadow Robot, where I work on the co-design of learning algorithms and robot embodiment for dexterous manipulation. I completed my PhD at the University of Edinburgh under the supervision of Prof. Michael Mistry.

My research lies at the intersection of embodied AI, robot learning, and dexterous manipulation. I am motivated by building intelligent robotic agents that can perceive, reason, and act effectively in contact-rich real-world environments. In particular, I aim to enable robots with human-level agility and intelligence, and even beyond-human dexterity, for challenging manipulation tasks.


Research Focus
======
My work focuses on multimodal robot learning, data-efficient imitation and reinforcement learning, long-horizon dexterous manipulation, and sim-to-real transfer for reliable deployment on real robot.


- Multimodal robot learning for dexterous manipulation, especially with tactile sensing
- Data-efficient imitation learning from limited demonstrations
- Efficient reinforcement learning for long-horizon dexterous tasks with sparse rewards
- Sim-to-real transfer for robust real-world deployment
- Co-design of robot learning algorithms and dexterous robot morphology
- Cross-embodiment learning and morphology evolution

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
