# 🚀 Quick Start Guide

## For Team Members New to Web Development

Welcome! This guide will get you editing the ShriekedIn website in **5 minutes**.

## ✅ What You Need

1. A **web browser** (Chrome, Firefox, Safari, Edge - you already have this!)
2. A **text editor** - Pick one:
   - **Notepad** (Windows) - Already installed!
   - **TextEdit** (Mac) - Already installed!
   - **VS Code** (Recommended) - Free download: https://code.visualstudio.com/

## 📝 Your First Edit (3 Steps)

### Step 1: Open the File
1. Navigate to the `mvp` folder
2. **Right-click** on `index.html`
3. Choose **"Open With"** → Your text editor

### Step 2: Make a Change
1. Find this line (around line 75):
   ```html
   <h1 class="text-5xl md:text-7xl font-bold text-white mb-6">
       🎃 ShriekedIn 🎃
   </h1>
   ```
2. Change "ShriekedIn" to "My Spooky Site"
3. **Save** the file (Ctrl+S or Cmd+S)

### Step 3: See Your Changes
1. **Double-click** `index.html` to open it in your browser
2. You should see "My Spooky Site" instead of "ShriekedIn"
3. **Congratulations!** You just edited a website! 🎉

## 🎨 Common Edits

### Change Colors

Find any color class and change it:
```html
<!-- Change orange to purple -->
<div class="bg-orange-500">
     Change to: bg-purple-500

<!-- Change text color -->
<p class="text-gray-700">
   Change to: text-purple-900
```

**Available colors**: orange, purple, red, blue, green, yellow, gray, pink, indigo

### Change Sizes

```html
<!-- Make text bigger -->
<h2 class="text-2xl">
    Change to: text-3xl or text-4xl

<!-- Add more spacing -->
<div class="p-4">
     Change to: p-6 or p-8
```

### Add Your Own Content

```html
<!-- Add a new paragraph -->
<p class="text-gray-700 mb-4">
    Your new paragraph goes here!
</p>

<!-- Add a new card (copy from existing cards) -->
<div class="bg-white rounded-lg shadow-md p-6">
    <h3 class="text-xl font-bold mb-2">New Card</h3>
    <p class="text-gray-600">Card content here</p>
</div>
```

## 📁 Files in This Folder

| File | What It Is | Edit This? |
|------|-----------|------------|
| `index.html` | Home page | ✅ Yes! |
| `events.html` | Events page | ✅ Yes! |
| `TEMPLATE.html` | Copy this to make new pages | ✅ Copy & edit |
| `README.md` | Detailed documentation | 📖 Read for help |
| `QUICK-START.md` | This file! | 📖 Reference |

## 🆕 Creating a New Page

1. **Copy** `TEMPLATE.html`
2. **Rename** it (e.g., `about.html`)
3. **Edit** the content section
4. **Link** to it from other pages:
   ```html
   <a href="about.html">About Us</a>
   ```

## 🐛 Troubleshooting

### My changes aren't showing!
- ✅ Did you **save** the file?
- ✅ Did you **refresh** your browser? (F5 or Ctrl+R)
- ✅ Try a **hard refresh**: Ctrl+F5 (Windows) or Cmd+Shift+R (Mac)

### The page looks broken!
- ❌ You might have deleted a `>` or `</div>` by accident
- ✅ **Undo** your last change (Ctrl+Z)
- ✅ Or compare with the original file

### Colors/styles not working?
- ❌ Tailwind class names must be exact (no typos!)
- ✅ Check the Tailwind docs: https://tailwindcss.com/docs
- ✅ Use the color/size examples in this guide

## 💡 Pro Tips

1. **Keep backups**: Copy your file before making big changes
2. **One change at a time**: Make small edits and test often
3. **Copy existing code**: Find something similar and copy it
4. **Use comments**: Add notes to yourself
   ```html
   <!-- This is a comment - it won't show on the page -->
   ```

## 📚 Next Steps

1. ✅ Make your first edit (follow Step 1-3 above)
2. ✅ Try changing colors
3. ✅ Try changing text sizes
4. ✅ Copy a card to add more content
5. ✅ Create a new page using TEMPLATE.html

## 🆘 Need Help?

- **Tailwind Docs**: https://tailwindcss.com/docs (look up any class)
- **HTML Basics**: https://www.w3schools.com/html/
- **Emoji Picker**: Press `Win + .` (Windows) or `Cmd + Ctrl + Space` (Mac)

---

**Remember**: You can't "break" anything permanently - just undo or re-copy the file!

Happy editing! 👻🎃
