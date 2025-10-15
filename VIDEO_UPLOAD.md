# Video Upload Solutions

## 🚨 File Size Issue: 40MB > 25MB GitHub Limit

Your video is 40MB, but GitHub web uploads are limited to 25MB. Here are your options:

### Option 1: Use Git LFS (Recommended) ✅

Git LFS is now configured for this repo. To upload your video:

1. **Clone the repository locally:**
   ```bash
   git clone https://github.com/PyThonicsML/navigating-the-night.git
   cd navigating-the-night
   ```

2. **Install Git LFS** (if not already installed):
   ```bash
   git lfs install
   ```

3. **Add your video file:**
   ```bash
   cp /path/to/your/Navigating_the_Night.mp4 .
   git add Navigating_the_Night.mp4
   git commit -m "Add NotebookLM video presentation"
   git push origin main
   ```

### Option 2: Compress Video (Quick Alternative)

Use online tools to compress your video to under 25MB:
- **Online Tools:** Clideo, CloudConvert, or VideoCompressor
- **Target:** Reduce from 40MB to ~20MB
- **Settings:** Lower bitrate but keep resolution

### Option 3: Alternative Hosting

If you prefer, we can:
1. Host video on your AWS S3 
2. Update the HTML to embed from S3
3. Keep the professional GitHub Pages interface

---

**After uploading the video (any method), remember to:**
1. Edit `index.html` 
2. Uncomment the `<video>` tag (around line 120)
3. Comment out the placeholder div

**Current Status:**
- ✅ Repository created
- ✅ Professional HTML page ready
- ✅ Git LFS configured for large files
- ⏳ Waiting for video upload
- ⏳ Waiting for GitHub Pages activation