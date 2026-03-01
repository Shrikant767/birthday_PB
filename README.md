# Birthday Website Setup Guide

## 📁 Folder Structure

First, create an `assets` folder in the same directory as `index.html`:

```
birthday_new/
├── index.html
└── assets/
    ├── photo1.jpg
    ├── photo2.jpg
    ├── photo3.jpg
    ├── photo4.jpg
    ├── photo5.jpg
    ├── photo6.jpg
    ├── photo7.jpg
    ├── photo8.jpg
    ├── photo9.jpg
    └── birthday-song.mp3
```

## 🎵 Adding Birthday Song

1. **Create the `assets` folder** in the same directory as `index.html`
2. **Place your birthday song** in the `assets` folder and name it exactly: `birthday-song.mp3`
3. The song will play automatically when the cake is cut!

### Supported Song Formats:
- MP3 (recommended)
- WAV
- OGG

## 📸 Adding Birthday Photos

1. **Create the `assets` folder** if not already created
2. **Add your photos** to the `assets` folder and name them:
   - `photo1.jpg`
   - `photo2.jpg`
   - `photo3.jpg`
   - `photo4.jpg`
   - `photo5.jpg`
   - `photo6.jpg`
   - `photo7.jpg`
   - `photo8.jpg`
   - `photo9.jpg`

3. Photos will appear in a **zigzag layout** after clicking "Here is the Surprise for You!"

### Photo Requirements:
- **Format**: JPG, PNG, or any image format
- **Size**: Square format preferred (e.g., 500x500px, 800x800px)
- **Quality**: Any quality works, but higher resolution looks better

## 🎂 Website Features

### Timeline:
1. ✨ **Hero Section** - Birthday wish greeting
2. 🎂 **Automatic Cake Building** - Watches as 4 layers are stacked (no user input needed)
3. 🕯️ **Candles Added** - 3 candles appear and light up automatically
4. 🔪 **Cut the Cake** - Click button to cut the cake (plays song!)
5. 🎉 **Surprise Button** - Shows photos and birthday message
6. 📸 **Zigzag Gallery** - Photos alternate left-right (zigzag pattern)
7. 💝 **Birthday Message** - Special birthday wishes at the bottom

## 🚀 How to Use

1. **Extract/Open** the folder where `index.html` is located
2. **Create `assets` folder** in the same directory
3. **Add your music** file as `birthday-song.mp3`
4. **Add your photos** as `photo1.jpg` through `photo8.jpg`
5. **Open `index.html`** in a web browser
6. **Watch the magic happen!** 🎉

## 📝 Customization

You can customize the birthday message by editing the following in `index.html`:

```javascript
// Find this line in the HTML:
<p id="wish-message">Wishing you a day filled with joy, laughter, and magical moments!</p>

// Change the text inside to your custom message!
```

## ⚠️ Notes

- The website works **offline** once all files are in place
- Song only plays when the cake is cut
- No setup needed - just add files to the `assets` folder
- Website is fully **mobile responsive**

**Enjoy the celebration! 🎂✨**
