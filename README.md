# ME25 Copyright

![Backdrop CMS](https://img.shields.io/badge/Backdrop-CMS-0073aa.svg)
![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-GPL--2.0--or--later-green.svg)

A lightweight, configurable copyright notice block for Backdrop CMS that automatically updates years and provides flexible display options.

## 🚀 Features

- **Automatic Year Updates** - Always shows current year without manual edits
- **Flexible Display Options** - Year range (2020-2025) or current year only (2025)
- **Admin Configuration** - Easy settings page for start year and display format
- **Lightweight** - No dependencies, minimal database queries
- **Cache Optimized** - Global caching for maximum performance

## 📦 Installation

1. Download and place in `modules/custom/` directory
2. Enable at **Modules** (`admin/modules`)
3. Configure at **Configuration → System → ME25 Copyright Settings** (`admin/config/system/me25-copyright`)
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
`templates/block--me25-copyright--copyright.tpl.php`

### CSS Styling:
```css
.me25-copyright {
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

## 📄 License

This project is licensed under the GPL-2.0-or-later License - see the [LICENSE](LICENSE) file for details.

## 🏢 About Max Elements

ME25 Copyright is maintained by [Max Elements](https://max-elements.com/), providing premium web development and cybersecurity solutions.

---

*Built with care for the Backdrop CMS community* 🛠️
