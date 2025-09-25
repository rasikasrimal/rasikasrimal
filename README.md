<h1 align="center">Rasika Srimal</h1>
<h3 align="center">Crafting resilient, data-driven software in the cloud</h3>

<p align="center">
  <samp>
    Full-stack developer · Cloud-native enthusiast · Lifelong learner
  </samp>
</p>

---

## 🧬 Bio

Hey there! I'm Rasika, a full-stack engineer who loves blending clean design with scalable architectures. I enjoy solving complex problems, building cloud-native solutions, and automating everything from CI/CD pipelines to data workflows. My current interests include platform engineering, developer experience, and empowering teams with observability tooling.

- ⚙️ Core skills: TypeScript, Python, React, Node.js, AWS, Terraform
- 🚀 Passions: Developer productivity, data visualization, and polished UX
- 🧠 Always learning: AI-assisted development, distributed systems, and DevOps culture

---

## 📊 GitHub Stats

<!-- GITHUB_STATS:START -->
<div align="center">
  <table>
    <tr>
      <td>
        <a href="https://github.com/rasikasrimal">
          <img alt="Rasika's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=rasikasrimal&count_private=true&show_icons=true&theme=radical" />
        </a>
      </td>
      <td>
        <a href="https://github.com/rasikasrimal">
          <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rasikasrimal&layout=compact&theme=radical" />
        </a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/rasikasrimal">
          <img alt="Contribution streak" src="https://streak-stats.demolab.com/?user=rasikasrimal&theme=radical" />
        </a>
      </td>
      <td>
        <a href="https://github.com/rasikasrimal?tab=repositories">
          <img alt="Pinned repository: portfolio" src="https://github-readme-stats.vercel.app/api/pin/?username=rasikasrimal&repo=portfolio&theme=radical" />
        </a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/rasikasrimal?tab=repositories">
          <img alt="Pinned repository: cloud-control-center" src="https://github-readme-stats.vercel.app/api/pin/?username=rasikasrimal&repo=cloud-control-center&theme=radical" />
        </a>
      </td>
      <td>
        <a href="https://github.com/rasikasrimal?tab=repositories">
          <img alt="Pinned repository: insightflow" src="https://github-readme-stats.vercel.app/api/pin/?username=rasikasrimal&repo=insightflow&theme=radical" />
        </a>
      </td>
    </tr>
  </table>
</div>
<!-- GITHUB_STATS:END -->

> ⏱️ _These SVGs refresh automatically every day via the GitHub Actions workflow below._

Inline daily SVG example:

![Daily updating contributions graph](https://github-readme-activity-graph.vercel.app/graph?username=rasikasrimal&theme=react-dark)

---

## 🌟 Featured Projects

- [Cloud Control Center](https://github.com/rasikasrimal/cloud-control-center) – Infrastructure-as-code toolkit and dashboards for automating multi-cloud provisioning.
- [InsightFlow](https://github.com/rasikasrimal/insightflow) – Real-time analytics pipeline with event-driven microservices and rich data visualizations.
- [UX Patterns Library](https://github.com/rasikasrimal/ux-patterns) – Accessible component system and design tokens for rapid UI prototyping.

---

## 📬 Contact & Social

<p align="center">
  <a href="mailto:rasika@example.com"><img src="https://img.shields.io/badge/Email-111827?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/rasikasrimal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://twitter.com/rasikasrimal"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"></a>
  <a href="https://rasikasrimal.dev"><img src="https://img.shields.io/badge/Website-111827?style=for-the-badge&logo=About.me&logoColor=white" alt="Website"></a>
</p>

---

## 🛠️ Automation Notes

<!-- README_GENERATION:START -->
This profile README is automatically regenerated every day using GitHub Actions. The workflow checks out the repository, updates the SVG badges above, and commits the refreshed README back to the main branch.
<!-- README_GENERATION:END -->

![Auto Update](https://github.com/rasikasrimal/rasikasrimal/actions/workflows/update-readme.yml/badge.svg)

---

### 📅 Daily GitHub Actions Workflow

```yaml
name: Update README stats

on:
  schedule:
    - cron: '0 0 * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v4

      - name: Pull latest README template
        run: |
          echo "Updating stats SVGs"
          # Add commands or scripts that refresh badges/statistics here.
          # e.g. curl -o stats.svg "https://github-readme-stats.vercel.app/api?username=rasikasrimal&count_private=true&show_icons=true&theme=radical"

      - name: Commit and push changes
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add README.md
          git commit -m "chore: refresh GitHub stats" || echo "No changes to commit"
          git push
```
