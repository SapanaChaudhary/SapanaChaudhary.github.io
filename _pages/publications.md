---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

{% include base_path %}

## Coding and Inference Time Search

{% assign coding_pubs = site.publications | where: "category", "Coding and Inference Time Search" | sort: "date" | reverse %}
{% for post in coding_pubs %}
  {% include publication-single.html post=post %}
{% endfor %}

## Reward Modeling

{% assign reward_pubs = site.publications | where: "category", "Reward Modeling" | sort: "date" | reverse %}
{% for post in reward_pubs %}
  {% include publication-single.html post=post %}
{% endfor %}

## RL for LLM Reasoning and Alignment

{% assign rl_pubs = site.publications | where: "category", "RL for LLM Reasoning and Alignment" | sort: "date" | reverse %}
{% for post in rl_pubs %}
  {% include publication-single.html post=post %}
{% endfor %}

## LLM Agents and Tool Use

{% assign agent_pubs = site.publications | where: "category", "LLM Agents and Tool Use" | sort: "date" | reverse %}
{% for post in agent_pubs %}
  {% include publication-single.html post=post %}
{% endfor %}

## Safe and Adaptive Sequential Decision Making

{% assign safe_pubs = site.publications | where: "category", "Safe and Adaptive Sequential Decision Making" | sort: "date" | reverse %}
{% for post in safe_pubs %}
  {% include publication-single.html post=post %}
{% endfor %}

## Deep Meta-RL and Imitation Learning

{% assign meta_pubs = site.publications | where: "category", "Deep Meta-RL and Imitation Learning" | sort: "date" | reverse %}
{% for post in meta_pubs %}
  {% include publication-single.html post=post %}
{% endfor %}
