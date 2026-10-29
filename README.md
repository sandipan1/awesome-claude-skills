# Awesome Claude Skills [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Claude Skills

## Contents 
- [What is a Claude skill](##What-is-a-Claude-skill)
- [Why is it relevant?](##Why-is-it-relevant)
- [Official Resources](#official-resources) 
- [Blogs & Articles](#blogs--articles)
- [Official skills](#official-skills)
- [Community-Skills](#community-skills)
- [Contributing](#contributing)



## What is a Claude skill
A Claude skill is a organized directory with `SKILL.md` along with instruction, code and resources that Claude can use to perform specific tasks. It works across Claude apps,API, Claude code. Refer to 
the official blog post in the [Official Resources](#official-resources) section for a comprehensive guide on how to build them.

## Why is it relevant
Skills allows you to perform specialized tasks using the tools and guidance that you needs. 
For e.g creating powerpoints following your organization's brand guidelines. 

Skills can also include code for Claude to execute as tools at its discretion. Claude can offload precise, deterministic operations—like parsing a PDF’s form fields, sorting large lists, or validating data—to code, then use its reasoning to orchestrate the workflow. 

## Official Resources 
- [Official Annnouncement](https://www.anthropic.com/news/skills)
- [Claude skills github](https://github.com/anthropics/skills/tree/main)
- [Building agent skills blog](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills)
- [Claude Skills Cookbook](https://github.com/anthropics/claude-cookbooks/tree/main/skills)

## Blogs & Articles
- [Simon Willison: Claude Skills](https://simonwillison.net/2025/Oct/10/claude-skills/) - Technical deep dive and skill extraction
- [Claude Skills Unlocks Enterprise-Grade AI Customization](https://www.startuphub.ai/ai-news/ai-video/2025/claude-skills-unlocks-enterprise-grade-ai-customization/) - Analysis of enterprise use cases
- [Claude just got customizable 'Skills'](https://www.tomsguide.com/ai/claude-just-got-customizable-skills-heres-how-they-could-supercharge-your-workflow) - Tom's Guide overview
- [How Anthropic's 'Skills' make Claude faster, cheaper, and more consistent](https://venturebeat.com/ai/how-anthropics-skills-make-claude-faster-cheaper-and-more-consistent-for) - VentureBeat analysis
- [Skills for Claude!](https://blog.fsck.com/2025/10/16/skills-for-claude/) - Community perspective


## Official skills 
### Document Skills

Skills for working with complex file formats:

- **[docx](https://github.com/anthropics/skills/tree/main/document-skills/docx)** - Create, edit, and analyze Word documents with support for tracked changes, comments, formatting preservation, and text extraction
- **[pdf](https://github.com/anthropics/skills/tree/main/document-skills/pdf)** - Comprehensive PDF manipulation toolkit for extracting text and tables, creating new PDFs, merging/splitting documents, and handling forms
- **[pptx](https://github.com/anthropics/skills/tree/main/document-skills/pptx)** - Create, edit, and analyze PowerPoint presentations with support for layouts, templates, charts, and automated slide generation
- **[xlsx](https://github.com/anthropics/skills/tree/main/document-skills/xlsx)** - Create, edit, and analyze Excel spreadsheets with support for formulas, formatting, data analysis, and visualization

### Design & Creative

- **[algorithmic-art](https://github.com/anthropics/skills/tree/main/algorithmic-art)** - Create generative art using p5.js with seeded randomness, flow fields, and particle systems
- **[canvas-design](https://github.com/anthropics/skills/tree/main/canvas-design)** - Design beautiful visual art in .png and .pdf formats using design philosophies
- **[slack-gif-creator](https://github.com/anthropics/skills/tree/main/slack-gif-creator)** - Create animated GIFs optimized for Slack's size constraints

### Development

- **[artifacts-builder](https://github.com/anthropics/skills/tree/main/artifacts-builder)** - Build complex claude.ai HTML artifacts using React, Tailwind CSS, and shadcn/ui components
- **[mcp-server](https://github.com/anthropics/skills/tree/main/mcp-server)** - Guide for creating high-quality MCP servers to integrate external APIs and services
- **[webapp-testing](https://github.com/anthropics/skills/tree/main/webapp-testing)** - Test local web applications using Playwright for UI verification and debugging

### Communication

- **[brand-guidelines](https://github.com/anthropics/skills/tree/main/brand-guidelines)** - Apply Anthropic's official brand colors and typography to artifacts
- **[internal-comms](https://github.com/anthropics/skills/tree/main/internal-comms)** - Write internal communications like status reports, newsletters, and FAQs

## Community Skills

More community skills coming soon! Submit a PR to add your skill.

- **[SPECTER](https://github.com/YannisKiefer/harvey-specter)** - Prepares negotiations and difficult-conversation drafts with evidence checks and clear boundaries.







## Contributing
Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To add a new skill or resource:

1. Fork this repository
2. Add your item to the appropriate section
3. Submit a pull request

Please ensure your contribution:
- Follows the existing format
- Includes a clear description
- Links to the relevant resource
- Is related to Claude Skills
