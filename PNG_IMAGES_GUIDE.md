# 🔦 Exorcism Challenge - PNG Images Guide

## 📁 Folder Structure
Place your PNG/JPG images in the `images/` folder with these exact names:

```
images/
├── room-background.jpg    - Main room background (1920x1080 recommended)
├── jumpscare.png         - Scary jumpscare image (1920x1080 recommended)
├── doll.png              - Creepy doll (Annabelle style)
├── crucifix.png          - Religious cross/crucifix
├── painting.png          - Haunted portrait with eyes
├── lamp.png              - Vintage or antique lamp
├── mirror.png            - Old ornate mirror
└── candle.png            - Gothic candle with flame
```

## 🎨 Image Requirements

### Background & Jumpscare:
- **room-background.jpg**: 1920x1080 pixels (Full HD) - JPG or PNG format
- **jumpscare.png**: 1920x1080 pixels (Full HD) - PNG with transparency preferred

### Object Images:
- **Resolution**: 200x200 pixels minimum (PNG format)
- **Background**: Transparent PNG preferred
- **Style**: Spooky/Gothic theme

### Specific Image Suggestions:

#### 🏠 **room-background.jpg**
- Haunted room, old mansion interior, or spooky basement
- Dark atmosphere with dramatic lighting
- Should look like a place where paranormal activity occurs
- Examples: Victorian parlor, old library, abandoned room

#### 👻 **jumpscare.png**
- Scary face, ghost, demon, or frightening creature
- High contrast, dramatic and scary
- Should fill most of the image for maximum impact
- Examples: Screaming ghost, demon face, scary clown

#### 🪆 **doll.png**
- Porcelain or vintage doll
- Preferably with visible eyes
- Annabelle-style or classic creepy doll

#### ✝️ **crucifix.png** 
- Wooden or metal cross
- Can be ornate or simple
- Gothic style preferred

#### 🖼️ **painting.png**
- Portrait with prominent eyes
- Dark/Victorian frame
- Should look like it's "watching"

#### 💡 **lamp.png**
- Vintage table lamp or candlestick
- Antique brass or ornate design
- Should look old-fashioned

#### 🪞 **mirror.png**
- Ornate hand mirror or wall mirror
- Gothic or baroque frame
- Should suggest reflection/spirits

#### 🕯️ **candle.png**
- Gothic candle with flame
- Melted wax details
- Dark/spooky atmosphere

## 🔧 How to Replace Images

1. **Save your PNG files** in the `images/` folder with exact names above
2. **The game now uses fallback system**: PNG images load first, SVG placeholders as backup
3. **Check file paths**: Make sure images are exactly in `images/doll.png`, etc.
4. **Test in browser**: Refresh page to see if PNG images load properly

### 🚨 Troubleshooting PNG Images:

If PNG images don't load, check:
- ✅ **File names match exactly**: `doll.png` (not `Doll.png` or `doll.PNG`)
- ✅ **Images folder exists**: `images/` folder in same directory as HTML file
- ✅ **File format**: Must be PNG format
- ✅ **Browser cache**: Try Ctrl+F5 to force refresh
- ✅ **File size**: Keep under 1MB per image for fast loading

### 📂 Current Status:
- **SVG placeholders**: Currently active (basic shapes)
- **PNG support**: Ready and waiting for your images
- **Fallback system**: Shows SVG if PNG not found

## 🎯 Current CSS Classes Ready for Images

The game is now configured for all custom images:

```css
/* Background */
.game-container { background: url('images/room-background.jpg'); }

/* Jumpscare */
.jumpscare { background: url('images/jumpscare.png'); }

/* Objects */
.doll { background-image: url('images/doll.png'); }
.crucifix { background-image: url('images/crucifix.png'); }
.painting { background-image: url('images/painting.png'); }
.lamp { background-image: url('images/lamp.png'); }
.mirror { background-image: url('images/mirror.png'); }
.candle { background-image: url('images/candle.png'); }
```

## ✨ NEW: Enhanced Visual Features

### 🎨 **Improved Readability**
- **Stronger text shadows** for better visibility
- **Background blur effects** behind text elements
- **Higher contrast** between text and background
- **Thicker borders** around UI elements

### 🖼️ **Custom Background Support**
- **Full HD resolution**: 1920x1080 recommended
- **Automatic fallback**: Shows gradient if image not found
- **Responsive scaling**: Works on all screen sizes

### 👻 **Custom Jumpscare**
- **Full screen scary image** when wrong answer
- **Enhanced animation** with scaling effects
- **PNG transparency support** for better integration

## 🎮 New Game Features Added

### 🎯 **Difficulty Levels**
- **Easy**: 4 objects, 90 seconds, 3 hints
- **Normal**: 6 objects, 60 seconds, 2 hints  
- **Nightmare**: 6 objects, 45 seconds, 1 hint

### 💡 **Hint System**
- Context-specific hints for each object
- Visual highlighting of haunted object
- Auto-hints when players struggle
- Limited hints per difficulty

### 🎨 **Enhanced UI**
- Better HUD with hint controls
- Difficulty selection screen
- Improved instructions
- Visual feedback for hints

### 🧠 **Smart Features**
- Objects adjust based on difficulty
- Progressive hint system
- Auto-assistance for struggling players
- Better feedback messages

## 🚀 Ready to Play!

Your game now has:
- ✅ **Custom background support** (1920x1080 recommended)
- ✅ **Custom jumpscare PNG** (full screen scary image)
- ✅ **Enhanced text readability** (stronger shadows, better contrast)
- ✅ **PNG object support** (just add your images)
- ✅ **3 difficulty levels** with smart hint system
- ✅ **Professional UI** with backdrop blur effects
- ✅ **Modal certainty integration** for English learning
- ✅ **Atmospheric effects** and smooth animations

### 📸 **Image Priority List:**
1. **room-background.jpg** - Main haunted room (most important for atmosphere)
2. **jumpscare.png** - Scary image for wrong answers
3. **Object PNGs** - Replace the 6 objects (doll, crucifix, etc.)

Simply add your images and the game will automatically use them with beautiful fallbacks!
