# Dynamic Copyright

![Backdrop CMS](https://img.shields.io/badge/Backdrop-CMS-0073aa.svg)
![License](https://img.shields.io/badge/license-GPL--2.0--or--later-green.svg)

A lightweight, configurable copyright notice block for Backdrop CMS that automatically updates years and provides flexible display options.

**This is an original Backdrop CMS module, not a port from Drupal. It provides modern, automated copyright management as a maintained alternative to abandoned solutions.**

## 🚀 Features

- **Automatic Year Updates** - Always shows current year without manual edits
- **Flexible Display Options** - Year range (2020-2025) or current year only (2025)
- **Start Year Configuration** - Set your site's launch year once
- **Admin Configuration** - Easy settings page for display format
- **Lightweight** - No dependencies, minimal database queries
- **Cache Optimized** - Global caching for maximum performance

## 📦 Installation

1. Download and extract to your `modules/` directory
2. Enable at **Modules** (`admin/modules`)
3. Configure at **Configuration → System → Dynamic Copyright Settings** (`admin/config/system/dynamic-copyright`)
4. Place block at **Structure → Block layout** (`admin/structure/block`)


## ⚙️ Configuration

### Display Options:
- **Year Range**: "© 2020-2025 Site Name" (requires start year)
- **Current Year Only**: "© 2025 Site Name" (ignores start year)

### Settings:
- **Show year range** - Toggle between range and current year display
- **Start year** - First year of your site's activity (only visible when range enabled)

## 🎯 Usage

1. **Enable module** and configure settings
2. **Place block** in any region (typically footer)
3. **Block automatically updates** each year - no maintenance needed!

## 🛠️ For Developers

### Template Override:
Override the block output by creating:
`templates/block--dynamic-copyright--copyright.tpl.php`


## 🤝 Contributing

We welcome contributions! Please feel free to:
- Submit issues and feature requests
- Create merge requests with improvements
- Suggest better configuration options

## 👤 Credits

**Developed by Max Elements**  
This is an original Backdrop CMS module, built specifically for the Backdrop ecosystem as part of the Max Elements Toolbox.

## 📄 License

This project is licensed under the GPL-2.0-or-later License - see the [LICENSE](LICENSE) file for details.

## 🏢 About Max Elements

Dynamic Copyright is maintained by [Max Elements](https://max-elements.com/), providing premium web development and cybersecurity solutions.

## 🧰 Max Elements Toolbox

**Max Elements Toolbox** represents our commitment to building and maintaining quality Backdrop CMS modules and themes for the community.

This toolbox includes:
- Essential utility modules (like Dynamic Copyright and Visual Language Switcher)
- Professional themes
- Client-proven solutions  
- All maintained long-term as part of our business offerings

Dynamic Copyright is part of this ongoing initiative to contribute quality tools to the Backdrop ecosystem.

---

*Built with care for the Backdrop CMS community* 🛠️
