# Hello World!

# Prompt to add a new blog:

# Adding a New Blog Post

## Step 1: Create New Blog Post File

1. Create a new HTML file in the `/posts` directory
2. Name format: `{next-number} {Title With Spaces}.html`
   (e.g., "010 Your New Blog Title.html")
3. Copy the structure from `post-template.html`
4. Update the following elements:
   - Title in `<title>` tag: "{Blog Title} - Eduardo Samayoa"
   - Main heading `<h1>`: Your blog title
   - Subtitle `<h2 class="subtitle">`: Your blog subtitle
   - Date `<time datetime="YYYY-MM-DD">`: Current date in format "Month DD, YYYY"
   - Content in `<div class="post-content">`: Your blog content
   - Keep all existing CSS classes and HTML structure
   - Maintain the navigation and footer sections unchanged

## Step 2: Update index.html

Add the following article block at the TOP of the `<section class="blog-posts">` section:

## Pre-publishing Checklist

- [ ] File name follows the numbering sequence
- [ ] All links in the new post are working
- [ ] Navigation links are correct (../index.html, etc.)
- [ ] Images are in the correct directory with proper paths
- [ ] Dates are consistent in both index.html and the blog post
- [ ] Content is properly formatted with paragraphs and headings
- [ ] Post displays correctly on both desktop and mobile
- [ ] HTML validates without errors
- [ ] No broken styles or layout issues
