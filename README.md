# OBS Multi-RTMP Plugin (Flatpak-ready)

This repository provides the original, unmodified **obs-multi-rtmp** plugin by [sorayuki](https://github.com/sorayuki/obs-multi-rtmp), packaged for **Flatpak users of OBS Studio**.

> ✅ **No code changes** — this is the exact same plugin as distributed by the original author.  
> ✅ **Tested on Linux (Manjaro)** with OBS Studio installed via Flatpak.

## 🔗 Official Resources
- **Original Source**: https://github.com/sorayuki/obs-multi-rtmp  
- **Plugin Page**: https://obsproject.com/forum/resources/multiple-rtmp-outputs-plugin.964/  
- **Author’s Site**: https://sorayuki.github.io/obs-multi-rtmp/  

## 📦 Installation (Flatpak)
1. Download the plugin archive.
2. Extract it into your Flatpak OBS configuration folder:  
   ```
   /home/user/.var/app/com.obsproject.Studio/config/obs-studio/
   ```
   *(Replace `user` with your actual username if different.)*

3. After extraction, the plugin files should be located as follows:

```
/home/user/.var/app/com.obsproject.Studio/config/obs-studio/
└── plugins/
    └── obs-multi-rtmp/
        ├── bin/
        │   └── 64bit/
        │       └── obs-multi-rtmp.so
        └── data/
            └── locale/
                └── en-GB.ini
```

Restart OBS Studio (Flatpak), and the plugin will load automatically.

> 💡 **Note**: This plugin enables **simultaneous streaming to multiple RTMP servers**. It can either **share the main encoder** (to reduce CPU usage) or use **dedicated encoders** with basic settings like bitrate.  
>  
> Originally created for VTubers — and **completely free**.  
> ⚠️ **Do not purchase** this plugin from third parties (e.g., Baidu Tieba user "maggot" or resellers on Xianyu). The author provides it **at no cost**.
