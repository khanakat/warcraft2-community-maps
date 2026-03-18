# Warcraft II Community Maps

Community-submitted Warcraft II maps for the [Warcraft II Community](https://github.com/Khanakat/Warcraft-II-Community) platform.

## 📁 Structure

```
Community/
├── authors/              # Individual author collections (organized by player count)
│   ├── <author1>/
│   │   ├── 2_players/
│   │   ├── 4_players/
│   │   ├── 8_players/
│   │   └── ...
│   └── <author2>/
│       └── ...
├── 2 Players/            # 2-player maps
├── 3 Players/            # 3-player maps
├── 4 Players/            # 4-player maps
├── 5 Players/            # 5-player maps
├── 6 Players/            # 6-player maps
├── 7 Players/            # 7-player maps
├── 8 Players/            # 8-player maps
├── Customs/              # Custom/modded maps
├── ChristmassCollection/  # Christmas-themed maps
└── RME/                  # RME (Resource Management Expert) maps
```

## 📊 Current Statistics

| Collection | Maps | Distribution |
|------------|-------|--------------|
| **Authors** | 840 | 8 players (470), 4 players (144), others (226) |
| **ChristmassCollection** | 18 | 8 players (13), others (5) |
| **RME** | 14 | 8 players (13), 4 players (1) |
| **Total** | **872** | - |

## 🤝 How to Contribute

### Submitting a New Map

1. Fork this repository
2. Add your `.pud` file to the appropriate category folder:
   - For 2-player maps: `Community/2 Players/YourMapName.pud`
   - For author collections: `Community/Authors/YourUsername/8 Players/MapName.pud`
3. Create a pull request to the `main` branch
4. Your map will be automatically validated and added to the pending queue
5. Wait for admin approval

### File Naming Guidelines

- **No spaces in filenames**: Use `My_Map.pud` instead of `My Map.pud`
- **Descriptive names**: Use `Desert_Warfare.pud` instead of `map1.pud`
- **Maximum length**: 255 characters (including `.pud` extension)

### Map Requirements

- **Format**: `.pud` (Warcraft II map format)
- **Validation**: Maps are automatically validated on submission
- **Duplicates**: Duplicate maps (by SHA-256 hash) are automatically rejected

## 📜 License

By submitting maps to this repository, you agree that:
- The maps may be displayed on the Warcraft II Community platform
- The maps remain your intellectual property
- Other users may download and play your maps

## 🔗 Links

- [Warcraft II Community Platform](https://warcraft2.site)
- [Documentation](https://github.com/Khanakat/Warcraft-II-Community/tree/main/docs)
- [Issue Tracker](https://github.com/Khanakat/warcraft2-community-maps/issues)

## 📝 Submission Workflow

```
1. Fork & Add Map
   ↓
2. Create Pull Request
   ↓
3. Webhook Triggered
   ↓
4. Automatic Validation
   ↓
5. Added to Pending Queue
   ↓
6. Admin Review
   ↓
7. Approved → Public Gallery
   ↓
8. Rejected → Deleted
```

---

**Last Updated:** 2026-03-18
