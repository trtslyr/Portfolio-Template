# STRAT 490R Portfolio Template

**Pure Quarto website.** Students edit only `.qmd` files.  
Beautiful output, zero local setup required.

## Quick Setup

1. **Enable GitHub Pages**: 
   - Go to Settings → Pages 
   - Source: "Deploy from a branch" → Change to "GitHub Actions"
   - Save
2. **Push this repo to GitHub** - The workflow will automatically run
3. **Site appears at**: `https://yourusername.github.io/repository-name`
4. **Give students**: Link to `STUDENT-GUIDE.md`

## How It Works
- Students edit `.qmd` files and commit changes
- GitHub Actions automatically builds the Quarto site  
- Site deploys to GitHub Pages automatically
- No setup needed for students!

## File Organization

```
✅ STUDENTS EDIT THESE:
├── index.qmd           📝 Homepage
├── about.qmd           📝 About page  
├── final-project.qmd   📝 Final project
├── assignments/        📁 All assignments
├── notes/             📁 Notes
└── images/            📁 Student images

❌ STUDENTS DON'T TOUCH:
├── _quarto.yml        ⚙️ Quarto config
├── .github/           🤖 Auto-deployment
└── README.md          📖 Instructions
```

## Student Workflow

1. Edit `.qmd` files (students stay in root and assignments/ folder)
2. Commit changes in GitHub
3. Site rebuilds automatically via GitHub Actions
4. Beautiful Quarto output!

## Local Development (Optional)

```bash
quarto render
quarto preview
```

That's it! Super clean and simple.