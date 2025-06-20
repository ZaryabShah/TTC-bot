# TikTok Automation Bot v4.1

🚀 **Advanced TikTok automation bot with custom comments and ActionChains precision**

## 🌟 Features

- ✅ **ActionChains Only**: Uses proven ActionChains click method for maximum accuracy
- 🎯 **Custom Comments**: Add personalized comments for each video URL
- ❤️ **Auto Like**: Automatically likes videos
- 💾 **Auto Save**: Saves videos to your collection
- 💬 **Smart Commenting**: Posts custom comments with human-like typing
- 👍 **Comment Liking**: Likes top-level comments on videos
- 🍪 **Cookie Support**: Login with saved cookies for authenticated sessions
- 🤖 **Anti-Detection**: Undetected Chrome with stealth features
- ⏸️ **Video Pausing**: Automatically pauses videos during interaction
- 🎨 **Colorful Console**: Beautiful colored output with progress tracking

## 📋 Requirements

- Python 3.7+
- Chrome browser installed
- Windows/Linux/Mac compatible

## 🚀 Installation

1. **Clone or download the project**
```bash
git clone <repository-url>
cd TT-Bot
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the bot**
```bash
python test2.py
```

## 📖 Usage

### Basic Usage

1. **Run the script**
   ```bash
   python test2.py
   ```

2. **Enter video URLs and comments**
   - Input TikTok video URLs one by one
   - For each URL, provide a custom comment
   - Press Enter with empty URL to finish

3. **Configure comment liking**
   - Choose how many top-level comments to like per video (0 for none)

4. **Start automation**
   - Press Enter to begin the automation process

### Example Workflow

```
--- Video #1 ---
URL: https://www.tiktok.com/@username/video/1234567890
Comment for this video: Amazing dance moves! 🔥

--- Video #2 ---
URL: https://www.tiktok.com/@username/video/0987654321
Comment for this video: This made my day! 😄

--- Video #3 ---
URL: (empty - to finish)

[+] How many top-level comments to like per video? (0=none) → 3
```

## 🍪 Cookie Authentication

For better results and to avoid login prompts:

1. **Export cookies** from your browser using a cookie export extension
2. **Save as `cookies.json`** in the project directory
3. **Format**: The bot expects JSON format with TikTok cookies

### Cookie File Structure
```json
[
  {
    "name": "cookie_name",
    "value": "cookie_value",
    "domain": ".tiktok.com",
    "path": "/",
    "secure": true,
    "httpOnly": false
  }
]
```

## ⚙️ Configuration

### XPath Selectors
The bot uses multiple XPath fallbacks for each element to ensure compatibility:
- Like buttons
- Save buttons  
- Comment buttons
- Share buttons
- Comment input fields
- Post buttons

### Timing & Delays
- **Human-like delays**: Random delays between 1-3 seconds
- **Page load timeout**: 20 seconds
- **Element timeout**: 10 seconds  
- **Video processing gap**: 20-30 seconds between videos

## 🛡️ Anti-Detection Features

- **Undetected Chrome**: Uses undetected-chromedriver
- **Custom User Agent**: Desktop Chrome user agent
- **WebDriver Property Hiding**: Removes automation indicators
- **Human Typing**: Character-by-character typing with random delays
- **Random Delays**: Human-like interaction timing

## 📊 Statistics Tracking

The bot tracks and displays:
- ❤️ **Likes**: Total videos liked
- 💬 **Comments**: Total comments posted  
- 💾 **Saves**: Total videos saved
- 📈 **Success Rate**: Percentage of successful video processing

## 🎨 Console Output

- 🔵 **Blue**: Headers and banners
- 🟢 **Green**: Success messages
- 🟡 **Yellow**: Warnings and info
- 🔴 **Red**: Errors
- 🟣 **Magenta**: Special actions
- 🔷 **Cyan**: Process steps

## 🔧 Troubleshooting

### Common Issues

1. **Chrome driver issues**
   ```bash
   pip install --upgrade undetected-chromedriver
   ```

2. **Element not found errors**
   - TikTok updates their UI frequently
   - The bot includes multiple XPath fallbacks
   - Check if you're logged in properly

3. **Rate limiting**
   - Increase delays between actions
   - Use authenticated sessions with cookies
   - Don't run too many videos at once

4. **Comments not posting**
   - Ensure you're logged in
   - Check if comments are enabled on the video
   - Verify comment content meets TikTok guidelines

### Debug Mode

For debugging, you can:
- Check console output for detailed error messages
- Modify timeout values in the code
- Add manual delays if needed

## ⚠️ Important Notes

- **Use Responsibly**: Respect TikTok's terms of service
- **Rate Limiting**: Don't overuse to avoid account restrictions  
- **Account Safety**: Use with accounts you don't mind getting limited
- **Content Guidelines**: Ensure comments follow platform guidelines
- **Updates**: TikTok may change their UI, requiring XPath updates

## 📝 Changelog

### v4.1
- ✅ ActionChains only implementation
- ✅ Custom comments for each URL
- ✅ Enhanced error handling
- ✅ Improved anti-detection
- ✅ Better console output
- ✅ Video pausing functionality

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly  
5. Submit a pull request

## 📄 License

This project is for educational purposes only. Use at your own risk and responsibility.

## 🆘 Support

If you encounter issues:
1. Check the troubleshooting section
2. Review console output for errors
3. Ensure all requirements are installed
4. Verify TikTok URLs are valid

---

**⚡ Happy Automating! ⚡**
#   T T C - b o t  
 