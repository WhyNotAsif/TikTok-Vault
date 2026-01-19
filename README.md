# TikTok Downloader || Vault

A professional Windows desktop application for downloading TikTok videos with advanced filtering, metadata export, and batch processing.

## 🎯 Features

- 📥 **Batch Download** - Download multiple TikTok videos at once
- 🏷️ **Hashtag Filtering** - Filter videos by hashtag  
- 👀 **View Count Filter** - Set minimum view threshold
- 📅 **Date Range Filtering** - Download videos within date ranges
- 💾 **Auto-Export** - Save metadata to Excel (.xlsx)
- 📊 **Rich Metadata** - Title, description, likes, views, upload date
- ⏸️ **Resume Support** - Skip already downloaded videos
- 🎨 **Responsive GUI** - Beautiful Tkinter interface
- 🖼️ **Auto Thumbnails** - Download video thumbnails

## 📦 Installation (Windows)

1. **Download** `TikTok-Downloader-Setup.exe` from [GitHub Releases](https://github.com/WhyNotAsif/tiktok-downloader/releases)
2. **Run** the MSI installer
3. **Launch** from Start Menu
4. **Data** saves to `Desktop/TikTok-Downloader/`

**Requirements:** Windows 10+ (64-bit), 500MB-2GB storage, Internet

## 🚀 Quick Start

1. Enter TikTok username (without @)
2. Set batch size (optional, default: 5)
3. Add filters (optional):
   - **Hashtag** - Filter by hashtag
   - **Min Views** - Minimum view count
   - **Start Date** - YYYY-MM-DD format
   - **End Date** - YYYY-MM-DD format
4. Click Download
5. Find files in `Desktop/TikTok-Downloader/downloads/`

## 📁 File Storage

```
Desktop/TikTok-Downloader/
├── downloads/
│   └── [username]/
│       ├── video1.mp4
│       ├── video1.jpg
│       ├── video2.mp4
│       └── video2.jpg
├── metadata.xlsx       # Excel export
├── data.json          # JSON backup
└── downloaded.txt     # Video ID log
```

## ⏰ License & Version

**Current Version:** 1.0.0 (January 2026)

### 🔐 Version Expiry
- ⚠️ **Expires:** December 31, 2027
- After expiry, app will not launch
- Download v2.0.0+ from GitHub Releases
- Check for updates regularly

### 📜 MIT License
**Free for personal AND commercial use**

**You can:**
- ✅ Use for personal projects
- ✅ Use for commercial purposes
- ✅ Modify and redistribute
- ✅ Include in your products

**You must:**
- ✅ Include the license
- ✅ State significant changes

**You cannot:**
- ❌ Hold author liable
- ❌ Remove copyright notice

[View Full License](LICENSE)

## 📋 Download Features Summary

| Feature | Details |
|---------|---------|
| **Video Format** | MP4 (highest quality) |
| **Thumbnails** | JPG format included |
| **Metadata** | Excel (.xlsx) + JSON |
| **Resume** | Auto-skip duplicates |
| **Batch Size** | 1-100+ configurable |
| **Date Filter** | YYYY-MM-DD format |
| **View Filter** | Configurable minimum |
| **Hashtag Filter** | Case-insensitive |

## 🔧 Technical Stack

**Built With:**
- Python 3.13+
- Tkinter (GUI Framework)
- yt-dlp (Video Download Engine)
- Pandas (Data Processing)
- openpyxl (Excel Export)
- PyInstaller (MSI Packaging)

**Dependencies:**
```
yt-dlp>=2024.01.01
pandas>=2.0.0
openpyxl>=3.1.0
```

## ⚠️ Disclaimer

**For PERSONAL USE ONLY**

Users must comply with:
- ✓ TikTok's Terms of Service
- ✓ Local copyright laws
- ✓ All applicable regulations in your country

**Author is NOT liable for:**
- Misuse of this software
- Copyright infringement
- Legal consequences
- Any damages caused by this application

Use responsibly and ethically.

## ❓ FAQ

**Q: Is it safe to use?**  
A: Yes! Open-source code, uses official yt-dlp library, zero data collection.

**Q: Can I use commercially?**  
A: Yes, under MIT License. Respect TikTok's Terms of Service.

**Q: What happens after December 31, 2027?**  
A: This version expires. Download v2.0.0+ from GitHub Releases.

**Q: Can I bypass the expiry?**  
A: No, it's a license protection feature. Always update to the latest version.

**Q: How much storage do I need?**  
A: Typically 500MB-2GB depending on video quality and quantity.

**Q: Do videos have watermarks?**  
A: No, yt-dlp downloads original quality without watermarks.

**Q: Is this affiliated with TikTok?**  
A: No, this is a third-party tool. Use responsibly and respect copyright laws.

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| "Access Denied" | Run as Administrator or check Desktop permissions |
| Videos not downloading | Verify username (no @), check internet, check for region locks |
| Metadata not saving | Check write permissions to Desktop, ensure disk space available |
| App won't start | Check if version expired, download newer release from GitHub |

## 📞 Support

- 🐛 [Report Bugs](https://github.com/WhyNotAsif/TikTok-Vault/issues)
- 💬 [Discussions](https://github.com/WhyNotAsif/TikTok-Vault/discussions)
- 👤 [Author](https://github.com/WhyNotAsif)

## 📝 Changelog

**v1.0.0 - January 2026**
- ✅ Initial release
- ✅ Batch download support
- ✅ Advanced filtering (hashtag, views, date)
- ✅ Excel & JSON export
- ✅ Responsive GUI
- ✅ MSI installer packaging
- ✅ Auto-save to Desktop
- ✅ Version expiry protection

---

**Made with ❤️ by WhyNotAsif**

If you find this useful, please ⭐ **Star this repository!**

*Last Updated: January 20, 2026*
