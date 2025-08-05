# ASL Flashcards - Introductions

Basic ASL vocabulary flashcards for beginners learning American Sign Language.

## Contents
- 5 introductory signs with video demonstrations
- Interactive flip-card interface
- Perfect for ASL 1 students

## How to Use
Click cards to flip between ASL video and English meaning.

---
Created by Dr. Hibbard for ASL education

# 🤟 Create Your Own ASL Flashcards

Transform your ASL videos into an interactive web app! This guide helps you create your own themed ASL flashcard deck (like STEM terms) using GitHub Pages.

## 📋 What You'll Need

- [ ] GitHub account (free at github.com)
- [ ] 5-10 ASL videos on your computer
- [ ] 15-30 minutes of your time

## 🎯 Step 1: Set Up Your Repository

### Option A: Use the Template (Recommended)
1. **Go to the original flashcard repository**
2. **Click the green "Use this template" button**
   - ![Template Button Example](https://docs.github.com/assets/cb-36544/images/help/repository/use-this-template-button.png)
3. **Name your new repository**
   - Example: `stem-asl-flashcards` or `chemistry-asl-cards`
4. **Make sure it's set to "Public"** (required for free GitHub Pages)
5. **Click "Create repository from template"**

### Option B: Fork the Repository
1. **Click the "Fork" button** in the top-right corner
2. **Choose your account** as the destination
3. **Rename if desired** in the repository settings

## 📹 Step 2: Upload Your Videos

1. **Click on the "videos" folder** in your new repository
2. **Click "Add file" → "Upload files"**
3. **Drag and drop your ASL videos** or click "choose your files"

### 🎯 Video Naming Tips:
- ✅ **Good names:** `Addition.mov`, `DNA.mov`, `Photosynthesis.mov`
- ❌ **Avoid:** `My video 1.mov`, `ASL_sign_for_math (1).mov`
- **Keep it simple:** Use letters, numbers, hyphens only
- **File formats:** `.mov` or `.mp4` work best

4. **Scroll to bottom** → Add commit message: "Upload STEM ASL videos"
5. **Click "Commit changes"**

## ✏️ Step 3: Edit Your Flashcard Content

1. **Click on `index.html`** in your repository
2. **Click the pencil icon** (✏️) to edit
3. **Find this section** (around line 200):

```javascript
const flashcards = [
    {
        video: "videos/Hello.mov",
        english: "HELLO",
        asl: "Wave hand greeting"
    },
    {
        video: "videos/Nice meet you.mov", 
        english: "NICE TO MEET YOU",
        asl: "Polite introduction response"
    },
    // ... more cards here
];
```

4. **Replace with your STEM content:**

```javascript
const flashcards = [
    {
        video: "videos/Addition.mov",
        english: "ADDITION",
        asl: "Math operation - combining numbers"
    },
    {
        video: "videos/DNA.mov", 
        english: "DNA",
        asl: "Genetic material - double helix"
    },
    {
        video: "videos/Photosynthesis.mov",
        english: "PHOTOSYNTHESIS", 
        asl: "Plants making food from sunlight"
    }
];
```

### 🎯 Flashcard Template:
```javascript
{
    video: "videos/YOUR-VIDEO-NAME.mov",
    english: "ENGLISH WORD OR PHRASE",
    asl: "Brief description or context"
},
```

**Important:** 
- Video filename must match exactly (including capitalization)
- Don't forget the comma after each `},`
- Keep English text short and clear

## 🎨 Step 4: Customize Your App Title

Find this section (around line 130):
```html
<h1>ASL Flashcards</h1>
<p>Introductions & Greetings</p>
```

Change to your theme:
```html
<h1>STEM ASL Flashcards</h1>
<p>Science & Math Terms</p>
```

## 💾 Step 5: Save Your Changes

1. **Scroll to bottom of the edit page**
2. **Add commit message:** "Update flashcards for STEM terms"
3. **Click "Commit changes"**

## 🌐 Step 6: Enable GitHub Pages

1. **Click "Settings"** (top menu in your repository)
2. **Scroll down to "Pages"** (left sidebar)
3. **Under "Source"** → Select "Deploy from a branch"
4. **Choose "main" branch** → Click "Save"
5. **Wait 2-3 minutes** for GitHub to build your site

### 🎉 Your Site is Live!
Your URL will be: `https://yourusername.github.io/your-repo-name`

## 📱 Step 7: Test Your Flashcards

1. **Open your GitHub Pages URL** in any browser
2. **Test features:**
   - [ ] Videos load and play
   - [ ] Clicking card flips to show English text
   - [ ] Previous/Next buttons work
   - [ ] Works on mobile devices

## 🔧 Troubleshooting

### Videos Not Loading?
- **Check exact filenames** in your videos folder
- **Make sure video names in code match exactly**
- **Try renaming videos** to simpler names (no spaces)

### Flashcards Not Flipping?
- **Hard refresh:** `Ctrl+Shift+R` (PC) or `Cmd+Shift+R` (Mac)
- **Check browser console** for error messages (F12 key)

### Site Not Loading?
- **Wait 5-10 minutes** after enabling GitHub Pages
- **Check repository is set to "Public"**
- **Verify GitHub Pages is enabled** in Settings

## 🎯 Tips for Success

### Video Best Practices:
- **Keep videos under 10MB** each for faster loading
- **3-10 second videos** work best for flashcards
- **Good lighting** makes signs clearer
- **Consistent background** looks more professional

### Content Organization:
- **Start with 5-10 cards** to test everything works
- **Group related terms** (all math, all chemistry, etc.)
- **Use consistent English formatting** (ALL CAPS or Title Case)

### Sharing Your App:
- **Copy your GitHub Pages URL**
- **Test on different devices** before sharing
- **Works great on phones** - users can add to home screen!

## 📚 Example Themes You Could Create:

- 🧪 **Chemistry:** Elements, reactions, lab equipment
- 🔬 **Biology:** Cell parts, body systems, organisms  
- 🧮 **Math:** Operations, geometry, algebra terms
- 🌍 **Earth Science:** Weather, rocks, planets
- 💻 **Computer Science:** Programming, hardware, internet
- 🏥 **Medical:** Body parts, symptoms, treatments

## 🆘 Need Help?

1. **Check your browser console** (F12) for error messages
2. **Compare your code** to the working original
3. **Double-check video filenames** match exactly
4. **Try with just 1-2 videos first** to test

## 🎉 Share Your Creation!

Once your flashcards are working:
- **Share the GitHub Pages URL** with students/colleagues
- **Users can bookmark** or add to home screen on mobile
- **Works offline** once initially loaded
- **No app store required** - just share the link!

---

**Happy signing!** 🤟 Your ASL flashcards will help make STEM concepts more accessible to the Deaf community.
