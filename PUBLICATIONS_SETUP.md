# Publications Page Setup Guide

## What Was Changed

Your publications page has been updated to display a small image next to each paper along with a 1-2 line summary.

## Changes Made

### 1. Individual Publication Files (`_publications/`)
Created 12 publication markdown files, one for each paper:
- Each file includes: title, authors, venue, excerpt (summary), paper URL, and teaser image path
- Files are named by year and paper name (e.g., `2024-risk-averse.md`)

### 2. Publications Page Template (`_pages/publications.md`)
- Updated to use Jekyll loops to automatically display publications by category
- Publications are organized into sections:
  - Coding and Inference Time Search
  - Reward Modeling
  - RL for LLM Reasoning and Alignment
  - LLM Agents and Tool Use
  - Safe and Adaptive Sequential Decision Making
  - Deep Meta-RL and Imitation Learning

### 3. Custom Display Template (`_includes/publication-single.html`)
- New template that displays:
  - Paper thumbnail image (left side)
  - Title, authors, venue, and year
  - 1-2 line summary
  - Links to paper, poster, slides, talk (when available)

### 4. Styling (`_sass/_archive.scss`)
- Added responsive CSS for publication items
- Images are 120px wide on desktop, flexible on mobile
- Clean, professional layout with proper spacing

### 5. Placeholder Images (`images/paper-thumbnails/`)
- Created directory for paper thumbnails
- Added placeholder images for all 12 papers
- Each image is currently a generic placeholder

## How to Add Your Paper Images

### Option 1: Extract from PDF
1. Open your paper PDF
2. Take a screenshot of the first page or a key figure
3. Resize to approximately 400x300px
4. Save as `images/paper-thumbnails/[paper-name].png`

Example filenames:
- `maxcode.png`
- `vericot.png`
- `risk-averse.png`
- etc.

### Option 2: Use a Key Figure
1. Export a key figure or diagram from your paper
2. Resize to approximately 400x300px
3. Save with the appropriate filename

### Option 3: Create a Custom Thumbnail
1. Create a simple graphic with your paper title and/or main idea
2. Use tools like Canva, PowerPoint, or Keynote
3. Export as PNG (400x300px)

## Customizing Summaries

To edit the summary for any paper:
1. Open the file in `_publications/` (e.g., `2024-risk-averse.md`)
2. Find the `excerpt:` field in the front matter
3. Update the text to your preferred 1-2 line summary
4. Keep it concise and descriptive

Example:
```yaml
excerpt: 'Introduces risk-averse objectives for LLM finetuning to ensure robust and safe model behavior across diverse scenarios.'
```

## Adding New Publications

To add a new publication:

1. Create a new file in `_publications/` following this template:

```yaml
---
title: "Your Paper Title"
collection: publications
permalink: /publication/2025-your-paper
excerpt: 'A concise 1-2 line summary of your paper.'
date: 2025-01-01
venue: 'Conference/Journal Name'
paperurl: 'https://arxiv.org/abs/...'
citation: 'Author list. (Year). Title. Venue.'
authors: 'Author1, <strong>Sapana Chaudhary</strong>, Author3'
category: 'Category Name'
teaser: 'paper-thumbnails/your-paper.png'
---
```

2. Add your paper image to `images/paper-thumbnails/your-paper.png`

3. If using a new category, update `_pages/publications.md` to include a section for it

## Categories

Current categories:
- Coding and Inference Time Search
- Reward Modeling
- RL for LLM Reasoning and Alignment
- LLM Agents and Tool Use
- Safe and Adaptive Sequential Decision Making
- Deep Meta-RL and Imitation Learning

## Testing Locally

To preview your changes:
```bash
bundle exec jekyll serve
```

Visit `http://localhost:4000/publications/` to see your updated publications page.

## File Structure

```
├── _publications/           # Individual publication markdown files
│   ├── 2026-maxcode.md
│   ├── 2025-vericot.md
│   └── ...
├── _pages/
│   └── publications.md     # Main publications page
├── _includes/
│   └── publication-single.html  # Display template
├── _sass/
│   └── _archive.scss       # Styling (see bottom of file)
└── images/
    └── paper-thumbnails/   # Paper thumbnail images
        ├── README.md
        ├── placeholder.png
        ├── maxcode.png
        └── ...
```

## Next Steps

1. Replace placeholder images with actual paper thumbnails
2. Review and refine the summaries for each paper
3. Test the page locally to ensure everything looks good
4. Commit and push your changes to GitHub Pages

Enjoy your enhanced publications page!
