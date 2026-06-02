# 💩 Fart Prank Website 💨

A hilarious interactive prank website that creates a fake "confidential report" claiming someone has farted, complete with fake loading screens, witness testimonies, statistics, and animations!

## 🎯 How It Works

This website dynamically inserts anyone's name into the prank. You can:
1. Send someone a personalized link with their name
2. Generate a QR code for them to scan
3. Let them enter their own name (or anyone's name) on the page

## 🚀 Quick Start (Testing Locally)

1. Open `index.html` in your web browser
2. You'll see a name input screen - enter any name to test the prank
3. Or add `?name=John` to the URL to skip the input screen

**Example:**
```
file:///path/to/index.html?name=Sarah
```

## 📦 Deploying to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and log in
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository name: Choose something inconspicuous like:
   - `confidential-report`
   - `urgent-findings`
   - `secret-docs`
   - `research-data`
   
   ⚠️ **Avoid names with "fart" or "prank" so the victim doesn't get suspicious!**

4. Make it **Public** (required for free GitHub Pages)
5. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A: Via GitHub Website (Easiest)**
1. On your repository page, click **"uploading an existing file"**
2. Drag and drop `index.html` (and optionally this README.md)
3. Click **"Commit changes"**

**Option B: Via Git Command Line**
```bash
cd fart-prank
git init
git add index.html README.md
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top navigation)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select **"main"** branch
5. Click **Save**
6. Wait 1-2 minutes for deployment

Your site will be live at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

## 🔗 Creating Personalized Links

### Basic Format
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/?name=John
```

### Examples
```
https://johndoe.github.io/confidential-report/?name=Sarah
https://johndoe.github.io/confidential-report/?name=Mike
https://johndoe.github.io/confidential-report/?name=Alexandra
```

### Tips for Sharing
- **Shorten the URL** using [bit.ly](https://bitly.com) or [tinyurl.com](https://tinyurl.com) to make it less suspicious
- **Create a story**: "Hey, check out this weird report I found about you..."
- **Be casual**: Don't make it too obvious it's a prank

## 📱 Generating QR Codes

### Method 1: Online QR Code Generators (Free & Easy)

**Recommended Sites:**
1. **[QR Code Generator](https://www.qr-code-generator.com/)**
   - Paste your personalized URL
   - Click "Create QR Code"
   - Download as PNG or SVG

2. **[QRCode Monkey](https://www.qrcode-monkey.com/)**
   - Paste URL
   - Customize colors/design (optional)
   - Download high-resolution QR code

3. **[QR.io](https://qr.io/)**
   - Simple and fast
   - Paste URL and download

### Method 2: Using QR Code Apps

**iOS:**
- Use built-in QR code generator in Safari (share button)
- Or download "QR Reader" app

**Android:**
- Google Lens
- "QR Code Generator" app

### Prank Ideas with QR Codes
- Print and leave on someone's desk with a note: "Scan for urgent information"
- Put it in a presentation slide: "Scan for research findings"
- Text it to someone: "Found this weird QR code with your name..."

## 🎭 Prank Scenarios

### Scenario 1: Direct Link
**Message:** "Hey [Name], someone sent me this weird confidential report about you... is this real? 😳"
**Link:** `https://your-site.github.io/?name=TheirName`

### Scenario 2: QR Code Mystery
**Leave a printed note:** "Confidential Research Findings - Scan for Access"
**Include QR code** with their name in the URL

### Scenario 3: Professional Prank
**Email subject:** "ACTION REQUIRED: Review Your Personnel File"
**Body:** "Please review the attached report at your earliest convenience."
**Link:** Make it look official

### Scenario 4: Generic Victim
**No URL parameter** - just send them the base link
They enter their own name (or anyone's!) and get pranked

## 🛠️ Customization Options

### Changing the Default Name
In `index.html`, line ~15 in the JavaScript:
```javascript
let targetName = 'YourDefaultName'; // Change this
```

### Modifying the Final Message
Find the `#name-reveal` section (around line 660) to customize the ending message.

### Adjusting Animations
All animations are in the CSS section - feel free to tweak timing, colors, etc.

## 🎨 Features

- 💀 Fake "hacking" loading screen with green Matrix-style text
- 💩 Custom poop emoji cursor with animated trail
- 📊 Animated "fart statistics" and skill bars
- 👥 Fake witness testimonies from neighbors, NASA, scientists, pets
- 🔊 Web Audio API-generated fart sound effects
- 💨 Interactive fart clouds and explosions
- 🎉 Confetti and heart animations at the reveal
- 📱 Fully responsive (works on mobile)
- 🎭 Sweet ending message revealing it's a prank

## 🔒 Privacy & Safety

- This website runs 100% in the browser (client-side only)
- No data is collected or sent anywhere
- No tracking or analytics
- Safe, harmless fun!

## 📝 License

Free to use for pranks, jokes, and laughs! 

## 💡 Pro Tips

1. **Test First**: Always test with your own name before pranking others
2. **Know Your Audience**: Make sure the person has a good sense of humor
3. **Timing Is Everything**: Catch them off-guard for maximum effect
4. **Have Fun**: The goal is laughter, not embarrassment!

## 🐛 Troubleshooting

**Website not loading?**
- Wait 2-3 minutes after enabling GitHub Pages
- Check that the repository is public
- Make sure the file is named `index.html` (case-sensitive)

**Name not appearing?**
- Check the URL format: `?name=John` (no spaces)
- Use `%20` for spaces in names: `?name=Mary%20Jane`

**QR code not scanning?**
- Make sure it's high resolution
- Ensure good lighting when scanning
- Try regenerating with a higher quality setting

---

**Made with 💩 and lots of giggles**

Enjoy pranking your friends and family!
