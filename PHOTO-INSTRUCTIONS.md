# How to Add Your Profile Picture

## Step 1: Save Your Photo
1. Save your profile picture as `om-photo.jpg` in the `om-pandey-portfolio` folder
2. Make sure the image is:
   - High quality (at least 300x300 pixels)
   - Square aspect ratio (1:1) for best results
   - JPG or PNG format
   - File size under 2MB for fast loading

## Step 2: Recommended Photo Specifications
- **Size**: 400x400 pixels or larger
- **Format**: JPG (for smaller file size) or PNG (for transparency)
- **Background**: Clean, professional background
- **Lighting**: Good lighting with clear visibility of your face

## Step 3: File Naming
Your photo should be named exactly: `om-photo.jpg`

## Step 4: Alternative Formats
If you want to use a PNG file instead:
1. Name it `om-photo.png`
2. Update the HTML file by changing `om-photo.jpg` to `om-photo.png` in two places:
   - Line 54: `<img src="om-photo.png" alt="Om Pandey" class="profile-pic">`
   - Line 111: `<img src="om-photo.png" alt="Om Pandey" class="about-profile-pic">`

## Step 5: Testing
After adding your photo:
1. Open `index.html` in your browser
2. Check if the image loads correctly in both the hero section and about section
3. Verify the image looks good on mobile devices

## Troubleshooting
- If the image doesn't appear, check the file name and location
- If the image looks distorted, ensure it's square (1:1 aspect ratio)
- If the file is too large, compress it using online tools like TinyPNG

## Current Setup
The portfolio is already configured to display your photo with:
- Impressive circular design with gradient border
- Hover effects and animations
- Responsive design for all devices
- Professional styling in both hero and about sections
