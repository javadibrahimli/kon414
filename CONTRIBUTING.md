# Contributing Guidelines

## Welcome Contributors

Thank you for your interest in contributing to the KON 414E Robotics Projects Showcase! This repository is designed as a **long-term archive** that will grow with each cohort of students taking KON 414E.

**Whether you're a current student or returning years later**, you're welcome to add your project to this showcase. This document provides comprehensive guidelines to ensure smooth collaboration and maintain high-quality standards across all submissions from multiple academic years.

---

## Table of Contents

1. [Getting Started](#getting-started)
2. [Contribution Process](#contribution-process)
3. [Project Requirements](#project-requirements)
4. [Code of Conduct](#code-of-conduct)
5. [Review Process](#review-process)
6. [Getting Help](#getting-help)

---

## Getting Started

### Prerequisites

Before contributing, ensure you have:
- A GitHub account
- Git installed on your local machine
- Your project repository publicly accessible on GitHub
- Basic knowledge of Markdown formatting
- Familiarity with pull request workflows

### Understanding the Repository

This repository serves as a centralized showcase for all KON 414E student projects. Each contribution adds to a growing collection of innovative robotics solutions developed throughout the course.

---

## Contribution Process

### Step 1: Fork the Repository

1. Navigate to the main repository
2. Click the **"Fork"** button in the top-right corner
3. This creates a copy of the repository under your GitHub account

### Step 2: Clone Your Fork

```bash
git clone https://github.com/javadibrahimli/kon414.git
cd kon414
```

### Step 3: Create a Feature Branch

Use descriptive branch names that reflect your contribution:

```bash
git checkout -b add-project-TEAMNAME
```

**Branch Naming Convention:**
- `add-project-[team-name]` for new project additions
- `update-project-[team-name]` for existing project updates
- `fix-[description]` for bug fixes or corrections

### Step 4: Add Your Project to README

Edit the `README.md` file and add a new row to the projects table. Follow this exact format:

```markdown
| **Your Project Name** | Member 1, Member 2, Member 3 | YYYY-YYYY | Technology 1, Technology 2, Technology 3 | [![Watch Demo](https://img.youtube.com/vi/VIDEO_ID/mqdefault.jpg)](https://youtube.com/watch?v=VIDEO_ID) | [![GitHub](https://img.shields.io/badge/GitHub-View%20Project-181717?style=flat&logo=github)](https://github.com/YOUR-REPO-LINK) |
```

**Important:** Replace `YYYY-YYYY` with your academic year (e.g., 2025-2026, 2026-2027, etc.)

**Demo/Video Options:**
- **YouTube Video**: `[![Watch Demo](https://img.youtube.com/vi/VIDEO_ID/mqdefault.jpg)](https://youtube.com/watch?v=VIDEO_ID)` (Replace VIDEO_ID with your YouTube video ID)
- **Google Drive**: `[![Demo](https://img.shields.io/badge/Demo-Watch%20Video-red?style=flat&logo=googledrive)](your-drive-link)`
- **No Demo**: Use `N/A` if you don't have a demo video yet

**Example:**
```markdown
| **Autonomous Warehouse Robot** | John Doe, Jane Smith, Alex Johnson | 2026-2027 | ROS2, SLAM, LiDAR, Python | [![Watch Demo](https://img.youtube.com/vi/ABC123/mqdefault.jpg)](https://youtube.com/watch?v=ABC123) | [![GitHub](https://img.shields.io/badge/GitHub-View%20Project-181717?style=flat&logo=github)](https://github.com/johndoe/warehouse-robot) |
```

### Step 5: Commit Your Changes

Write clear, descriptive commit messages:

```bash
git add README.md
git commit -m "Add [Project Name] by [Team Name]"
```

**Good Commit Messages:**
- `Add Autonomous Warehouse Robot by Team Alpha`
- `Update Tomato Agribot project information`
- `Fix broken repository link for Navigation Robot`

**Avoid:**
- `Update README`
- `Changes`
- `Fix`

### Step 6: Push to Your Fork

```bash
git push origin add-project-TEAMNAME
```

### Step 7: Create Pull Request

1. Navigate to your fork on GitHub
2. Click **"Compare & Pull Request"** button
3. Fill in the pull request template:

**Pull Request Title Format:**
```
Add [Project Name] - [Team Name]
```

**Pull Request Description Template:**
```markdown
## Project Information
- **Project Name:** [Your project name]
- **Team Members:** [List all members]
- **Repository:** [Link to repository]

## Brief Description
[2-3 sentences about your project]

## Key Features
- Feature 1
- Feature 2
- Feature 3

## Checklist
- [ ] Followed table format exactly
- [ ] All links tested and working
- [ ] Team members listed correctly
- [ ] No merge conflicts
- [ ] Read contributing guidelines
```

4. Submit the pull request

---

## Project Requirements

### Repository Requirements

Your project repository MUST include:

**Essential Files:**
- `README.md` with comprehensive project documentation
- Source code with proper organization
- `LICENSE` file (MIT recommended)
- `.gitignore` appropriate for your technology stack

**README.md Should Contain:**
- Project title and description
- Installation instructions
- Dependencies and requirements
- Usage examples
- Screenshots or demo videos
- Team member information
- Acknowledgments

### Documentation Standards

**Code Quality:**
- Well-commented code
- Consistent naming conventions
- Modular and organized structure
- No hardcoded credentials or sensitive data

**Documentation Quality:**
- Clear and concise language
- Step-by-step instructions
- Troubleshooting section
- References and citations where applicable

---

## Code of Conduct

### Our Standards

All contributors must:
- Be respectful and professional in all interactions
- Provide constructive feedback
- Accept responsibility for mistakes
- Focus on collaborative problem-solving
- Respect diverse perspectives and experiences

### Unacceptable Behavior

The following will not be tolerated:
- Harassment or discriminatory language
- Trolling or insulting comments
- Personal or political attacks
- Publishing others' private information
- Any conduct inappropriate in a professional setting

---

## Review Process

### What Happens After Submission

1. **Automated Checks**: Basic formatting and link validation
2. **Maintainer Review**: Manual review of submission quality
3. **Feedback**: Comments or requested changes (if needed)
4. **Approval**: Merge into main repository
5. **Notification**: Confirmation of successful contribution

### Review Criteria

Your submission will be evaluated based on:
- **Formatting**: Follows table structure exactly
- **Completeness**: All required information provided
- **Links**: Repository link works and is publicly accessible
- **Quality**: Project repository meets documentation standards
- **Accuracy**: Team member names and project details are correct

### Timeline

- Initial review: Within 2-3 business days
- Follow-up responses: Within 1-2 business days
- Final approval: After all requirements are met

---

## Getting Help

### Common Issues

**Q: My pull request has merge conflicts. What do I do?**
A: Sync your fork with the main repository and resolve conflicts locally.

```bash
git remote add upstream https://github.com/ORIGINAL-OWNER/kon414-projects.git
git fetch upstream
git merge upstream/main
# Resolve conflicts
git push origin add-project-TEAMNAME
```

**Q: I made a mistake in my submission. How do I fix it?**
A: Make changes in your branch and push again. The pull request will update automatically.

**Q: The badge link isn't working. What's wrong?**
A: Ensure you're using the exact format provided and your repository URL is correct.

### Support Channels

- **GitHub Issues**: For technical problems with the repository
- **Pull Request Comments**: For questions about your specific submission
- **Course Forum**: For academic or course-related questions

---

## Additional Resources

### Markdown Guide
- [GitHub Markdown Documentation](https://docs.github.com/en/get-started/writing-on-github)
- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

### Git Resources
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)

---

<div align="center">

Thank you for contributing to the KON 414E Robotics Projects Showcase!

Your contribution helps build a valuable resource for the robotics community.

</div>
