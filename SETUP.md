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
- **snake.yml** - Generates contribution graph snake animation (runs daily at midnight)

### 3. Files Structure

```
ShriabhayS/
├── README.md              # Main profile README
├── .github/
│   └── workflows/
│       ├── metrics.yml    # GitHub metrics workflow
│       └── snake.yml      # Snake animation workflow
└── output/                # Generated snake animation (created by workflow)
```

### 4. Widgets Included

✅ Animated typing header
✅ Visitor counter
✅ GitHub followers/stars badges
✅ Social media links
✅ GitHub stats cards
✅ GitHub streak stats
✅ GitHub activity graph
✅ GitHub trophies
✅ GitHub profile summary cards
✅ Contribution snake animation
✅ GitHub metrics (comprehensive)
✅ Tech stack badges
✅ Experience sections
✅ Education & certifications
✅ Awards & honors
✅ Projects showcase

### 5. Customization

You can customize:
- Colors in badges (currently using blueviolet/purple theme)
- Timezone in metrics.yml (currently set to Australia/Melbourne)
- UTC offset in profile summary cards (currently set to +10)
- Add more widgets from https://github.com/maurodesouza/profile-readme-generator

### 6. First Run

After pushing to GitHub:
1. The workflows will run automatically
2. The snake animation will be generated in the `output/` folder
3. GitHub metrics will be generated and saved as `github-metrics.svg`
4. All widgets will start updating automatically

### 7. Notes

- The snake animation updates daily
- GitHub metrics update daily
- All stats are live and update automatically
- Visitor counter updates in real-time
- Profile views counter updates in real-time

---

**Made with ❤️ for Shriabhay S**

