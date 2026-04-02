# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Project Overview

This is a Chinese educational knowledge resource repository (`mswnlz/edu-knowlege`) that serves as a curated collection of educational resources, learning methods, and knowledge sharing materials.

## Common Commands

### Resource Management
```bash
# Create new monthly resource file
touch $(date +%Y%m).md

# View recent resource files
ls -la 2025*.md | head -5

# Search for educational topics
grep -r "教育" *.md
grep -r "knowledge" *.md
```

## Content Guidelines

- Use consistent formatting with descriptive titles
- Keep resource titles clean; do not append obsolete branding or domain suffixes. If a site link is needed, use https://pan.devmini.space
- Organize resources by subject and educational level
- Provide both Chinese and English descriptions where applicable
