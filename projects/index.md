---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Explore our open-source projects, research code repositories, and datasets. We actively maintain several repositories on our GitHub organization including course materials, challenge baselines, and research implementations.

Notable projects include:
- **NNCV** - Neural Networks for Computer Vision course materials
- **SurgeNet** - Self-supervised learning for surgical foundation models
- **RARE25** - Challenge submissions and baselines for reliable AI in endoscopy
- **DisCoPatch** - ICCV 2025 implementation for medical image analysis
- **YOLOv5-6D-Pose** - 6-DoF pose estimation for X-ray applications

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
