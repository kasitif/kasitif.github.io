# Image Guide for Your CV Site

This guide explains how to add images to your website for the consultancy and projects pages.

## Image Directory Structure

```
assets/images/
├── profile.jpg                          # Your profile photo (for Bio page)
├── consultancy/                         # Consultancy project images
│   ├── malawi-cbfews.jpg
│   ├── climate-action-callander.jpg
│   ├── undp-malawi.jpg
│   └── snv-kenya.jpg
└── projects/                            # Research project images
    ├── phd-flood-mapping.jpg
    ├── sepa-social-media.jpg
    ├── water-hyacinth.jpg
    ├── tanzania-streamflow.jpg
    ├── kenya-flood-damage.jpg
    └── training-workshops.jpg
```

## Required Images

### Profile Photo (Bio Page)
**File:** `assets/images/profile.jpg`
- **Recommended size:** 400x400 pixels (will be displayed as 200x200)
- **Format:** JPG or PNG
- **Description:** Professional headshot with plain background
- **Note:** Image will be displayed as a circle

### Consultancy Project Images
**Location:** `assets/images/consultancy/`

1. **malawi-cbfews.jpg**
   - Community meeting or flood monitoring equipment
   - Photos from field installations or training sessions

2. **climate-action-callander.jpg**
   - River Teith or Callander landscape
   - Flood risk areas or nature-based solutions

3. **undp-malawi.jpg**
   - Community volunteers or monitoring equipment
   - Training sessions or early warning activities

4. **snv-kenya.jpg**
   - Water points in arid regions
   - Pastoral communities or water sampling activities

**Recommended size:** 500x400 pixels (landscape orientation)
**Format:** JPG

### Research Project Images
**Location:** `assets/images/projects/`

1. **phd-flood-mapping.jpg**
   - SAR satellite imagery showing floods
   - Drone in field or field equipment
   - Computer screen showing flood maps

2. **sepa-social-media.jpg**
   - Dashboard/visualization of social media monitoring
   - SEPA offices or flood response activities

3. **water-hyacinth.jpg**
   - Lake Victoria showing water hyacinth infestation
   - Satellite imagery comparison (before/after)

4. **tanzania-streamflow.jpg**
   - Screenshot of streamflowmonitor.rcmrd.org
   - River monitoring or hydrological station

5. **kenya-flood-damage.jpg**
   - Flood satellite imagery (Sentinel-1 or Sentinel-2)
   - Maps showing flood extent

6. **training-workshops.jpg**
   - Training session photos
   - Participants working on computers
   - Group photos from workshops

**Recommended size:** 500x400 pixels (landscape orientation)
**Format:** JPG

## How to Add Images

### Option 1: Before Uploading to GitHub

1. Collect your images with the filenames listed above
2. Place them in the correct folders:
   - Profile photo → `assets/images/`
   - Consultancy → `assets/images/consultancy/`
   - Projects → `assets/images/projects/`
3. Upload everything to GitHub together

### Option 2: After Site is Live

1. Go to your GitHub repository
2. Navigate to `assets/images/consultancy/` or `assets/images/projects/`
3. Click "Add file" → "Upload files"
4. Drag and drop your images
5. Commit changes
6. Site will rebuild automatically

## Using Placeholder Images (Temporary)

If you don't have all images yet, you can use free stock photos from:

- **Unsplash:** https://unsplash.com
- **Pexels:** https://pexels.com
- **Pixabay:** https://pixabay.com

Search terms to try:
- "flood monitoring"
- "satellite imagery"
- "community meeting africa"
- "river landscape"
- "water resources"
- "data visualization dashboard"

## Image Optimization Tips

1. **Compress images** before uploading:
   - Use tools like TinyPNG.com or Squoosh.app
   - Target size: 100-300 KB per image

2. **Crop to correct aspect ratio:**
   - Profile: Square (1:1)
   - Projects/Consultancy: Landscape (5:4 or 4:3)

3. **File naming:**
   - Use lowercase
   - Use hyphens instead of spaces
   - Keep names descriptive but short

## What If I Don't Have Images?

The site will still work without images! The layout will adjust automatically. However, images make your site much more engaging and professional. Priority order:

1. **Profile photo** (highest priority - makes Bio page professional)
2. **Key project images** (Tanzania streamflow, water hyacinth)
3. **Consultancy images** (if available)

You can also remove image sections from specific pages by editing the `.md` files and removing the `<div class="project-image">` sections.

## Testing Images Locally

If you're running Jekyll locally:

1. Add images to the folders
2. Run `bundle exec jekyll serve`
3. Check how they look at `localhost:4000`
4. Adjust if needed

## Image Permissions

**Important:** Only use images you have rights to:
- Your own photos ✓
- Photos from your projects (with permission) ✓
- Free stock photos with appropriate license ✓
- Copyrighted images without permission ✗

For project photos, consider:
- Screenshots of your own work
- Satellite imagery (usually open access - check license)
- Photos you took during fieldwork
- Organization photos (with permission)

---

## Quick Start Checklist

- [ ] Get professional headshot (profile.jpg)
- [ ] Collect or create 4 consultancy images
- [ ] Collect or create 6 project images
- [ ] Optimize images (compress, resize)
- [ ] Upload to correct folders
- [ ] Check site after deployment

---

*Your site will look great even with just a profile photo and a few key images!*
