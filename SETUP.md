# GitHub Profile Setup Guide

## 🚀 Setup Instructions

### 1. GitHub Actions Secrets

To enable the GitHub Metrics workflow, you need to set up a Personal Access Token:

1. Go to GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Generate a new token with the `repo` scope
3. Go to your repository settings → Secrets and variables → Actions
4. Add a new secret named `METRICS_TOKEN` with your token value

### 2. Workflows

The following workflows are set up:

- **metrics.yml** - Generates GitHub metrics (runs daily at midnight)
- **snake.yml** - Generates contribution graph snake animation (runs daily at midnight and on push)

### 3. Files Structure

```
ShriabhayS/
├── README.md              # Main profile README
├── SETUP.md               # This setup guide
├── github-metrics.svg     # Generated GitHub metrics (optional, can be added to README)
├── .github/
│   └── workflows/
│       ├── metrics.yml    # GitHub metrics workflow
│       └── snake.yml      # Snake animation workflow
└── output/                # Generated snake animation
    └── github-contribution-grid-snake.svg
```

### 4. Widgets Included

✅ Animated typing header
✅ Visitor counter
✅ GitHub followers/stars badges
✅ Social media links (LinkedIn, Gmail, GitHub)
✅ GitHub stats cards (overall stats and top languages)
✅ GitHub streak stats
✅ GitHub activity graph
✅ GitHub trophies
✅ Contribution snake animation
✅ Tech stack badges (organized by category)
✅ Contact information

### 5. Customization

You can customize:
- Colors in badges (currently using blueviolet/purple theme)
- Timezone in metrics.yml (currently set to Australia/Melbourne)
- Tech stack badges (add or remove technologies)
- Contact information in README.md

### 6. First Run

After pushing to GitHub:
1. The workflows will run automatically
2. The snake animation will be generated in the `output/` folder
3. GitHub metrics will be generated and saved as `github-metrics.svg` (optional - not currently displayed in README)
4. All stats will start updating automatically

### 7. Notes

- The snake animation updates daily and on push to main branch
- GitHub metrics update daily (if workflow is enabled)
- All stats are live and update automatically
- Visitor counter updates in real-time
- Profile stats update automatically via external APIs

---

**Made with ❤️ for Shriabhay S**
