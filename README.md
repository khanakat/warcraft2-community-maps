# Warcraft II Community Maps

Community-submitted Warcraft II maps for the [Warcraft II Community](https://github.com/Khanakat/Warcraft-II-Community) platform.

## 📁 Structure

```
warcraft2-community-maps/
├── authors/              # Individual author collections (organized by player count)
│   ├── <author1>/
│   │   ├── 2_players/
│   │   ├── 4_players/
│   │   ├── 6_players/
│   │   ├── 8_players/
│   │   └── ...
│   └── <author2>/
│       └── ...
├── christmass/           # Christmas-themed maps (organized by player count)
│   ├── 4_players/
│   ├── 5_players/
│   ├── 6_players/
│   ├── 7_players/
│   └── 8_players/
└── rme/                  # RME (Resource Management Expert) maps (organized by player count)
    ├── 4_players/
    ├── 6_players/
    └── 8_players/
```

## 📊 Current Statistics

| Collection | Maps | Distribution |
|------------|-------|--------------|
| **Authors** | 834 | 8 players, 4 players, 2 players, etc. |
| **Christmass** | 18 | 4, 5, 6, 7, 8 players |
| **RME** | 14 | 4, 6, 8 players |
| **Total** | **866** | - |

## 🤝 How to Contribute

### Submitting a New Map

1. Fork this repository
2. Add your `.pud` file to the appropriate location:

   **For author collections (recommended):**
   ```
   authors/<your_username>/<n_players>/YourMapName.pud
   ```
   Example: `authors/john_doe/4_players/Desert_Warfare.pud`

   **Available player count folders:**
   - `2_players/` - 2-player maps
   - `4_players/` - 4-player maps
   - `6_players/` - 6-player maps
   - `8_players/` - 8-player maps

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

### Special Collections

- **`authors/`** - Individual author map collections organized by player count
- **`christmass/`** - Christmas-themed maps for the holiday season
- **`rme/`** - RME (Resource Management Expert) maps - specialized economic scenarios

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
