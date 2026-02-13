# Images Directory

This folder contains all images for the website.

## Required Images

Upload your club photos here with these exact filenames:

### Homepage Images
- `hero-group-photo.jpg` (1920x800px) - Main hero banner
- `meeting-discussion.jpg` (800x600px) - Meeting discussion scene
- `presentation-skill.jpg` (800x600px) - Member presenting
- `meeting-evaluator.jpg` (800x600px) - Evaluation session
- `networking-event.jpg` (800x600px) - Networking/social
- `leadership-development.jpg` (800x600px) - Leadership activities

### Blog Images
- `blog-random-role.jpg` (600x400px)
- `blog-table-topics.jpg` (600x400px)
- `blog-intranet.jpg` (600x400px)
- `blog-covid.jpg` (600x400px)
- `blog-evaluation.jpg` (600x400px)
- `blog-placeholder.jpg` (600x400px)

### Page Images
- `club-awards.jpg` (800x600px)
- `club-officers.jpg` (800x600px)

## Using Placeholder Images

Until you have actual images, you can use placeholders:

**Method 1: Placehold.co**
Replace src in HTML:
```html
<img src="https://placehold.co/800x600/1a4d7d/ffffff?text=Toastmasters+7">
```

**Method 2: Unsplash**
```html
<img src="https://source.unsplash.com/800x600/?business,presentation">
```

## Optimization Tips

Before uploading:
1. Resize to recommended dimensions
2. Compress using TinyPNG.com
3. Target file size < 500KB
4. Use JPG format for photos

## Upload Methods

**GitLab Web Interface:**
1. Navigate to this folder in GitLab
2. Click "Upload file"
3. Drag and drop images
4. Commit changes

**Git Command Line:**
```bash
cp /path/to/your/images/* .
git add .
git commit -m "Add website images"
git push
```

Site will automatically rebuild with new images!
