# DokiTR

<p align="center">
  <img src="assets/logo.png" alt="DokiTR Logo" width="200"/>
</p>

<p align="center">
  <strong>A feature-rich webtoon, manhwa, and manga reader with extensive Turkish content support</strong>
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

---

## Overview

**DokiTR** is an open-source mobile application for reading webtoons, manhwa, and manga. Built as a fork of [Doki](https://github.com/hanatsumi/doki) and [Kotatsu](https://github.com/KotatsuApp/Kotatsu), DokiTR significantly expands content accessibility with a strong emphasis on Turkish-language sources.

While Kotatsu offers approximately **800 content sources**, DokiTR provides access to **over 1,200 sources**, making it the ideal choice for Turkish-speaking readers and anyone seeking broader content availability.

## Features

### 🌐 Extensive Content Sources
- **1,200+ sources** for webtoons, manhwa, and manga
- **Premium Turkish content support** with dedicated providers
- All sources from Kotatsu and Doki, plus hundreds more
- Multi-language support with Turkish prioritization

### 📱 User Experience
- Clean, intuitive interface
- Offline reading with chapter downloads
- Customizable reading experience (orientation, zoom, brightness)
- Reading progress tracking and history
- Bookmark and favorites management

### 🔍 Discovery & Organization
- Advanced search across all sources
- Category and genre filtering
- Personalized recommendations
- Library management with custom collections
- Multi-source aggregation

### ⚙️ Technical Features
- Open-source and community-driven
- Regular updates and source maintenance
- Privacy-focused (no tracking)
- Android-native performance
- Backup and restore functionality

## Differences from Kotatsu and Doki

| Feature | Kotatsu | Doki | DokiTR |
|---------|---------|------|--------|
| **Total Sources** | ~800 | Fork of Kotatsu | **~1,200** |
| **Turkish Sources** | Limited | Limited | **Extensive** |
| **Focus** | General | General | **Turkish + General** |
| **Community** | International | International | **Turkish + International** |

DokiTR maintains compatibility with Kotatsu and Doki's core features while dramatically expanding Turkish content availability and overall source count.

## Installation

### From Releases
1. Download the latest APK from the [Releases](https://github.com/agnogad/Dokitr-build/releases) page
2. Enable "Install from Unknown Sources" in your Android settings
3. Install the APK file
4. Launch DokiTR and start reading

### Build from Source
```bash
# Clone the repository
git clone https://github.com/agnogad/dokitr.git
cd dokitr

# Build the project
./gradlew assembleRelease

# The APK will be located in app/build/outputs/apk/release/
```

### Requirements
- Android 5.0 (API 21) or higher
- ~50MB free storage space

## Screenshots

> **Note:** Screenshots will be added soon. Check back for visual previews of the app interface, reading experience, and library management features.

<!-- 
Placeholder for screenshots:
- Home/Browse screen
- Reader interface
- Library management
- Source selection
- Settings panel
-->

## Contributing

We welcome contributions from the community! DokiTR thrives on open-source collaboration.

### How to Contribute

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Areas for Contribution
- 🌐 Adding new content sources
- 🇹🇷 Improving Turkish translations
- 🐛 Bug fixes and performance improvements
- 📖 Documentation enhancements
- ✨ Feature development

### Source Contribution Guidelines
When adding new sources:
- Ensure compliance with the source website's terms of service
- Test thoroughly across different content types
- Document any special requirements or limitations
- Follow existing parser patterns

## Disclaimer

**Important:** DokiTR does not host any content. All manga, manhwa, and webtoon content is fetched from third-party sources. The app acts as a content aggregator and reader interface.

- Content availability depends on third-party sources
- DokiTR is not responsible for content on external websites
- Users should respect copyright and terms of service of content providers
- This app is intended for personal use only

## Support

- **Issues:** Report bugs and request features via [GitHub Issues](../../issues)
- **Discussions:** Join conversations in [GitHub Discussions](../../discussions)
- **Updates:** Follow the project for release notifications

## Roadmap

- [ ] Additional source integrations
- [ ] Enhanced recommendation engine
- [ ] Improved offline reading capabilities
- [ ] User synchronization across devices
- [ ] Community-driven feature additions

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### Attribution

DokiTR is a fork of:
- [Kotatsu](https://github.com/KotatsuApp/Kotatsu) - Original codebase
- [Doki](https://github.com/hanatsumi/doki) - Derivative work

We are grateful to the original developers and the open-source community for their contributions.

---

<p align="center">
  Made with ❤️ by the DokiTR community
</p>

<p align="center">
  <a href="#dokitr">Back to Top</a>
</p>
