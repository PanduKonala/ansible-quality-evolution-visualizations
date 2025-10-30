# IaC Quality Framework - Supplementary Materials

Supplementary visualizations for the PhD thesis: **"Policy-Based Quality Assessment Framework for Infrastructure as Code"**

## Overview

This repository provides animated visualizations demonstrating how Infrastructure as Code (IaC) repositories evolve across eight development philosophies throughout their lifecycle.

## Contents

### Animated Visualizations

1. **nginx.nginx Repository Evolution** (`animations/nginx_official_evolution.mp4`)
   - 805 commits across 3 development stages
   - Shows transformation from velocity-focused to quality-focused development
   
2. **geerlingguy.nginx Repository Evolution** (`animations/geerlingguy_evolution.mp4`)
   - 245 commits demonstrating individual developer patterns
   - Shows rapid quality establishment followed by maintenance mode

## Development Philosophies

The visualizations track alignment with eight philosophies:
- Move Fast & Break Things
- Startup MVP
- Lean Infrastructure
- Documentation-Driven Development
- DevSecOps Zero-Trust
- Enterprise Fortress
- Chaos Engineering (Netflix)
- Sustainable Engineering

## Dataset

- **Repositories Analyzed**: 26,986 Ansible Galaxy repositories
- **Temporal Coverage**: 2014-2024
- **Framework**: Two-tier policy-based quality assessment

**Folder Structure:**
```
iac-quality-framework-supplementary/
├── README.md
├── LICENSE
├── animations/
│   ├── nginx_official_evolution.mp4
│   ├── geerlingguy_evolution.mp4
