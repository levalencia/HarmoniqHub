# Release History

## 1.1.0 November 2025
**Major Release: AI-Powered Track Intelligence & Queue Enhancements**

### 🎯 Track Intelligence
- **Overall Data Confidence**: New comprehensive score combining Shazam, AI enrichment, and filename parsing
- **DJ Pattern Detection**: Automatic recognition of mashups, transitions, and remixes
- **Track Type Fixer**: Manual correction tool for misclassified tracks
- **Spam Filtering**: Automatic removal of phone numbers, URLs, and promotional text from albums and labels

### 🎵 Enhanced Identification
- **Identify Everything**: One-click identification combining all services (Shazam, AI, audio features, genres, popularity)
- **Track Changes Summary**: View exactly what was updated after identification
- **Undo Support**: Revert changes immediately after identification
- **Improved Genre Detection**: Essentia ML with 519 music styles from Discogs taxonomy

### 📋 Queue Improvements
- **Full Editing**: Right-click tracks in Queue to edit metadata
- **Context Menus**: All identification options available in Queue
- **Drag & Drop**: Drag tracks from library to Queue for instant playback
- **Visual Indicators**: Processing status with contextual labels

### 🎨 UI/UX Enhancements
- **Larger Edit Track Window**: 1000x800 pixels for better readability
- **Collapsible Sections**: Audio Features, Mood/Theme, Spotify Features
- **File Path Button**: Quick access to track location in Finder
- **Simplified AI Suggestions**: Streamlined playlist recommendation dialog

### ⚡ Performance
- **Optimized Backups**: 10-second startup delay, 1-hour throttling, background priority
- **Batch Processing**: 1000 tracks at a time for favorites to reduce memory pressure
- **Enhanced Logging**: Better diagnostics throughout backup process

### 🐛 Bug Fixes
- Fixed album/label spam filtering
- Fixed AI model parameter handling
- Fixed playlist suggestion crashes
- Comprehensive SwiftData relationship safety checks

## 1.0.3 October 2025
**AI Enrichment & Backups**

### Metadata & AI Features
- **AI Metadata Enrichment**: Automatic enrichment via AcoustID, MusicBrainz, Discogs, Spotify, and LLM parsing
- **Audio Features Detection**: AI-powered danceability, energy, mood, and theme analysis
- **Detection Settings**: Customizable AI models and thresholds for audio analysis
- **Genre Filtering**: Banned genres list with configurable detection thresholds
- **Mood & Theme Fields**: New tag-based interface for track emotions

### Backups & Data Management
- **Automatic Backups**: At startup for Playlists, Libraries, and Searches
- **Restore Capability**: Direct restore from Settings with confirmations
- **Favorites Preservation**: Playlist backups now include and restore favorites
- **Combined Snapshots**: Single unified library backup across all libraries
- **Background Operations**: Non-blocking backup and restore

### User Management
- **Enhanced Registration**: Anonymous mode, notification preferences, device info
- **Account Metadata**: Display creation date and last seen timestamps
- **Better Date Formatting**: Relative time for recent dates

### Additional Features
- **Folder Status**: Custom statuses with icons and colors via right-click
- **Star Rating**: In player view
- **Random Track Picker**: Dice button for 10 random tracks across libraries
- **Match Settings**: Control save behavior by Shazam quality level
- **App Logo**: Added to Assets

### Bug Fixes
- Context menu actions use correct folder selection
- Updated deprecated `onChange` modifier syntax
- Replaced deprecated AVAsset duration API with async load

## 1.0.2 August 2025
- Added text search functionality (saved searches with resync capability)
- Added export to disk on playlists or folders
- Added match quality field to measure Shazam detection accuracy
- ⚠️ Breaking: Requires deleting and reimporting Music Libraries

## 1.0.1 June 2025
- Added several playlist templates
- Added ID3 Tag sync from database to files
- Option to auto sync libraries when app starts
- Minor performance improvements

## 1.0.0 May 2025
**First Release**
- Import music libraries
- Favorites list
- Playlist creation with templates
- Detect BPM and Key
- Detect Popularity

---

# HarmoniqHub

The intelligent music library manager for DJs and music enthusiasts.

**HarmoniqHub** combines AI-powered audio analysis with comprehensive metadata enrichment to help you organize, discover, and perfect your music collection.

## Key Features

- 🎵 **Smart Track Identification**: Shazam, AI enrichment, and intelligent filename parsing
- 🎧 **DJ-Optimized**: Automatic detection of mashups, transitions, and remixes
- 📊 **Audio Analysis**: AI-powered BPM, key, energy, danceability, mood detection
- 🎨 **Custom Organization**: Folder statuses, playlists, smart searches
- 💾 **Automatic Backups**: Safe experimentation with instant restore
- 🔍 **Advanced Search**: Persistent searches with automatic updates
- 🎯 **Data Confidence**: Overall quality scores for metadata reliability

## Get Help & Share Feedback

Have questions, feature requests, or bugs to report?

👉 **[Join the Discussion](https://github.com/levalencia/HarmoniqHub/discussions)**

We'd love to hear from you!

---

**Download:** Available on the Mac App Store  
**Requires:** macOS 13.0 or later
