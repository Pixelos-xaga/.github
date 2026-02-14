# PixelOS for Xaga

Welcome to the official PixelOS organization for Xiaomi MT6895-based devices (codename: xaga)!

## About

This organization maintains PixelOS Android builds for the following devices:
- **POCO X4 GT**
- **Redmi K50i**
- **Redmi Note 11T Pro**
- **Redmi Note 11T Pro+**

These devices share the same MediaTek Dimensity 8100 (MT6895) platform and use the internal codename "xaga".

## What is PixelOS?

PixelOS is a custom Android ROM that brings a clean, Pixel-like experience to your device. It aims to provide:
- Stock Android aesthetics with Pixel features
- Regular security updates
- Performance optimizations
- Enhanced customization options
- Stability and battery life improvements

## Repository Structure

Our organization contains several key repositories:

### Core Repositories
- **[PIXELOS16](https://github.com/Pixelos-xaga/PIXELOS16)** - Main ROM manifest and build scripts
- **[pixelos-releases](https://github.com/Pixelos-xaga/pixelos-releases)** - Official ROM releases and changelogs

### Device Trees
- **[android_device_xiaomi_xaga](https://github.com/Pixelos-xaga/android_device_xiaomi_xaga)** - Device-specific configuration for xaga
- **[android_device_xiaomi_mt6895-common](https://github.com/Pixelos-xaga/android_device_xiaomi_mt6895-common)** - Common configurations for MT6895 platform

### Hardware & Vendor Support
- **[android_hardware_mediatek](https://github.com/Pixelos-xaga/android_hardware_mediatek)** - MediaTek-specific hardware abstraction layers
- **[android_device_mediatek_sepolicy_vndr](https://github.com/Pixelos-xaga/android_device_mediatek_sepolicy_vndr)** - SELinux policies for MediaTek devices
- **[proprietary_vendor_xiaomi_miuicamera-xaga](https://github.com/Pixelos-xaga/proprietary_vendor_xiaomi_miuicamera-xaga)** - MIUI Camera proprietary blobs

## Installation

### Prerequisites
- Unlocked bootloader
- Backup of your data

## Building from Source

### Build Environment Setup
```bash
# Install dependencies (Ubuntu/Debian)
sudo apt-get install bc bison build-essential ccache curl flex \
    g++-multilib gcc-multilib git git-lfs gnupg gperf imagemagick \
    lib32ncurses5-dev lib32readline-dev lib32z1-dev liblz4-tool \
    libncurses5 libncurses5-dev libsdl1.2-dev libssl-dev libxml2 \
    libxml2-utils lzop pngcrush rsync schedtool squashfs-tools \
    xsltproc zip zlib1g-dev openjdk-11-jdk python-is-python3
```

## Features

- ✨ Pixel UI/UX experience
- 🔋 Optimized battery performance
- 🎨 Material You theming
- 📱 Pixel-exclusive features ported
- 🔒 Monthly security patches
- ⚡ Performance enhancements
- 🎯 MediaTek Dimensity 8100 optimizations

## Device Specifications

| Feature | Specification |
|---------|--------------|
| SoC | MediaTek Dimensity 8100 (MT6895) |
| CPU | Octa-core (4x2.85 GHz Cortex-A78 & 4x2.0 GHz Cortex-A55) |
| GPU | Mali-G610 MC6 |
| Memory | 6GB / 8GB / 12GB RAM |
| Storage | 128GB / 256GB UFS 3.1 |
| Display | 6.6" FHD+ IPS LCD, 144Hz |
| Camera | 64MP + 8MP + 2MP (Rear), 16MP (Front) |
| Battery | 5080mAh, 67W fast charging |

## Contributing

We welcome contributions! Here's how you can help:

1. **Bug Reports**: Open an issue with detailed information
2. **Code Contributions**: Fork, make changes, and submit a pull request
3. **Testing**: Help test builds and report issues
4. **Documentation**: Improve guides and documentation

### Contribution Guidelines
- Follow Android code style guidelines
- Test your changes before submitting
- Provide clear commit messages
- Reference related issues in pull requests

## Support & Community

- **Issues**: Report bugs via GitHub Issues

## Credits & Thanks

- **PixelOS Team** - For the amazing ROM base
- **LineageOS Team** - For device tree references and inspiration
- **All Contributors** - For their time and effort

## License

This project includes components under various licenses:
- Apache 2.0 (AOSP and most custom ROM code)
- MIT License (specific components)
- GPL v2 (Linux kernel)

Individual repositories contain their specific license information.

## Disclaimer

- We are not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed
- YOU are choosing to make these modifications, and if you point the finger at us for messing up your device, we will laugh at you
- Your warranty is now void (if it wasn't already)

---

**Made with ❤️ by the PixelOS-xaga team**

*Bringing Pixel experience to MediaTek devices*
