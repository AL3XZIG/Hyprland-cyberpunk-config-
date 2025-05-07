```markdown
# <width="30"/> Contribution Guide

Thank you for considering contributing to the Cyberpunk Hyprland project! This guide will help you set up the development environment and submit changes.

## 🛠️ Development Setup

### Prerequisites
- Arch Linux or derivative (recommended)
- Hyprland 0.30.0+
- Git 2.40+
- Basic knowledge of:
  - Wayland protocols
  - Hyprland config syntax
  - Bash scripting

### Installation
```bash
# Fork and clone the repo
git clone https://github.com/YOUR_USERNAME/cyberpunk-hyprland.git
cd cyberpunk-hyprland

# Create development branch
git checkout -b feat/your-feature-name
```

## 🔧 Workflow

### Branch Naming
| Prefix | Use Case |
|--------|----------|
| `feat/` | New features |
| `fix/` | Bug fixes |
| `docs/` | Documentation |
| `refactor/` | Code improvements |

### Making Changes
1. Test config changes:
```bash
hyprctl reload
```

2. Verify package installations:
```bash
~/.config/hypr/scripts/pkg_verify.sh
```

## 📝 Pull Requests

### Requirements
- [ ] Tested on fresh Arch install
- [ ] No conflicts with existing features
- [ ] Updated documentation
- [ ] Added changelog entry

### Submission Process
1. Push to your fork:
```bash
git push origin feat/your-feature-name
```
2. Open PR with this template:
```
## Change Type
[ ] Feature [ ] Fix [ ] Refactor [ ] Docs

## Description
<!-- What does this change accomplish? -->

## Testing
<!-- How was this tested? -->

## Screenshots
<!-- For UI changes -->
```

## 🐛 Issue Reporting

Use this template when creating issues:
```
### Environment
- OS: 
- Hyprland Version: 
- GPU: 

### Description
<!-- What's the problem? -->

### Steps to Reproduce
1. 
2. 
3. 

### Expected Behavior
<!-- What should happen? -->

### Screenshots/Logs
<!-- Error messages or visual glitches -->
```

## 🎨 Style Guide

### Config Files
- Use 2 space indentation
- Section headers with `# ====` borders
- Alphabetize keybinds/categories

### Scripts
```bash
# Good
windowrulev2 = float, class:^(kitty)$

# Bad
windowrule=float,title:^(kitty)
```

## 💡 Feature Requests

Suggest new features via GitHub Discussions with:
- Use case description
- Proposed implementation
- Example config snippet

## 🏆 Recognition

All significant contributions will:
- Be listed in CREDITS.md
- Receive Cyberpunk-themed contributor badge
```markdown
![Contributor](https://img.shields.io/badge/Cyberpunk-Choomba_Contributor-ff00ff)
```

## ❓ Questions?

 Write me in telegram- @Zhilkin1010

---

*"Wake up, Samurai. We've got a DE to burn."* - Project Mantra
```
