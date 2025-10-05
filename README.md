# Copyright Block

![Backdrop CMS](https://img.shields.io/badge/Backdrop-CMS-0073aa.svg)
![License](https://img.shields.io/badge/license-GPL--2.0--or--later-green.svg)

A lightweight, configurable copyright notice block for Backdrop CMS that automatically updates years and provides flexible display options.

**This module is a new module for Backdrop and while it is not a port of the Drupal module of the same name, it provides the same features and functionality that users may expect if they have used the Drupal module in Drupal 7 or above.**

## 🚀 Features

- **Automatic Year Updates** - Always shows current year without manual edits
- **Flexible Display Options** - Year range (2020-2025) or current year only (2025)
- **Admin Configuration** - Easy settings page for start year and display format
- **Lightweight** - No dependencies, minimal database queries
- **Cache Optimized** - Global caching for maximum performance

## 📦 Installation

1. Download and place in `modules/custom/` directory
2. Enable at **Modules** (`admin/modules`)
3. Configure at **Configuration → System → Copyright Block Settings** (`admin/config/system/copyright-block`)
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
`templates/block--copyright-block--copyright.tpl.php`

### CSS Styling:
```css
.copyright-block {
  font-size: 0.9em;
  color: #666;
  text-align: center;
}
```

## 🤝 Contributing

We welcome contributions! Please feel free to:
- Submit issues and feature requests
- Create merge requests with improvements
- Suggest better configuration options

## 👤 Credits

**Developed by Max Elements**  
This is an original Backdrop CMS module, not a port from Drupal. 
Built specifically for the Backdrop ecosystem as part of the Max Elements Toolbox.

## 📄 License

This project is licensed under the GPL-2.0-or-later License - see the [LICENSE](LICENSE) file for details.

## 🏢 About Max Elements

Copyright Block is maintained by [Max Elements](https://max-elements.com/), providing premium web development and cybersecurity solutions.

## 🧰 Max Elements Toolbox

**Max Elements Toolbox** represents our commitment to building and maintaining quality Backdrop CMS modules and themes for the community.

This toolbox includes:
- Essential utility modules (like Copyright Block and Language Switcher)
- Professional themes
- Client-proven solutions  
- All maintained long-term as part of our business offerings

Copyright Block is part of this ongoing initiative to contribute quality tools to the Backdrop ecosystem.

---

*Built with care for the Backdrop CMS community* 🛠️
