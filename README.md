<h1 align="center">Rasika Srimal</h1>
<h3 align="center">Building intelligent, end-to-end data products across cloud, ML, and analytics</h3>

<p align="center">
  <samp>
    Full-stack Engineer · ML Engineer · Data Scientist &amp; Analyst
  </samp>
</p>

---



<p align="center">
  <a href="mailto:hello@rasikasrimal.dev"><img src="https://img.shields.io/badge/Email-111827?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/rasikasrimal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" alt="LinkedIn"></a>
  <a href="https://twitter.com/rasikasrimal"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&amp;logo=twitter&amp;logoColor=white" alt="Twitter"></a>
  <a href="https://www.youtube.com/@rasikasrimal"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&amp;logo=youtube&amp;logoColor=white" alt="YouTube"></a>
  <a href="https://rasikasrimal.dev"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&amp;logo=vercel&amp;logoColor=white" alt="Website"></a>
</p>

---


## 📊 GitHub Stats

<!-- GITHUB_STATS:START -->
<div align="center">
  <table>
    <tr>
      <td>
        <a href="https://github.com/rasikasrimal">
          <img alt="Rasika's GitHub stats" src="https://github-readme-stats.vercel.app/api?username=rasikasrimal&amp;count_private=true&amp;show_icons=true&amp;theme=radical" />
        </a>
      </td>
      <td>
        <a href="https://github.com/rasikasrimal">
          <img alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rasikasrimal&amp;layout=compact&amp;theme=radical" />
        </a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/rasikasrimal">
          <img alt="Contribution streak" src="https://streak-stats.demolab.com/?user=rasikasrimal&amp;theme=radical" />
        </a>
      </td>
      <td>
        <a href="https://github.com/rasikasrimal?tab=repositories">
          <img alt="Pinned repository: Heartlytics" src="https://github-readme-stats.vercel.app/api/pin/?username=rasikasrimal&amp;repo=Heartlytics&amp;theme=radical" />
        </a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/rasikasrimal?tab=repositories">
          <img alt="Pinned repository: veilmarket-mvp" src="https://github-readme-stats.vercel.app/api/pin/?username=rasikasrimal&amp;repo=veilmarket-mvp&amp;theme=radical" />
        </a>
      </td>
      <td>
        <a href="https://github.com/rasikasrimal?tab=repositories">
          <img alt="Pinned repository: saga-foundry" src="https://github-readme-stats.vercel.app/api/pin/?username=rasikasrimal&amp;repo=saga-foundry&amp;theme=radical" />
        </a>
      </td>
    </tr>
  </table>
</div>
<!-- GITHUB_STATS:END -->

![Daily updating contributions graph](https://github-readme-activity-graph.vercel.app/graph?username=rasikasrimal&amp;theme=react-dark)


---



### 📅 Daily GitHub Actions Workflow

Automated updates to the stats section are handled by [`update-readme.yml`](.github/workflows/update-readme.yml):

```yaml
name: Update README stats

on:
  schedule:
    - cron: '0 0 * * *'
  workflow_dispatch:

jobs:
  refresh:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v4

      - name: Update dynamic README assets
        run: |
          echo "Updating stats SVGs"
          # This is where you would call scripts or APIs that rebuild the stat images.
          # Example (uncomment when ready):
          # curl -o metrics.svg "https://github-readme-stats.vercel.app/api?username=rasikasrimal&count_private=true&show_icons=true&theme=radical"

      - name: Commit and push changes
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add README.md
          git commit -m "chore: refresh GitHub stats" || echo "No changes to commit"
          git push
```
