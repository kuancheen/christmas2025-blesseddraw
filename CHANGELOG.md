# Changelog

All notable changes to this project will be documented in this file.

## [v1.9.1] - 2024-12-19

### Changed
- **History Copied Notification**: Replaced the browser `alert()` with a custom, theme-consistent modal that supports closing via button, overlay click, or 'Esc' key.

## [v1.9.0] - 2024-12-19

### Added
- **Multi-Trigger Interaction**:
    - Prize boxes are now clickable to toggle status (Active/Disabled/Claimed).
    - The "Blessed Draw" title header is now clickable to trigger the draw.
- **Export Features**:
    - Added "Copy to Clipboard" button to Draw History.
    - Added "Download as CSV" button to Draw History.

## [v1.8.0] - 2024-12-19

### Changed
- **Prize Limit**: Increased the maximum number of simultaneous prize boxes from 10 to **20**.
- **UI/Layout**: Optimized the layout for large prize counts, defaulting to 5 items per row for better readability.

## [v1.7.6] - 2025-12-19

### Added
- **Compliance Audit**: Standardized project structure and documentation.
    - Added missing badges to `README.md` (SemVer, Status).
    - Standardized `index.html` comment header.
    - Added `.gitignore`.
    - Added `.github/workflows/static.yml` for automated GitHub Pages deployment.
    - Renamed and updated `version-update.md` workflow.

## [v1.7.5] - 2025-12-17

### Changed
-   **Branding**: Refined visual identity to match event theme.
    -   **Title**: Changed main "Blessed Draw" title to **White** (`text-white`) with drop shadow for better contrast.
    -   **Background**: Updated to a vibrant **Royal Blue** (`#2b50c8`) to align with official event assets.

## [v1.7.4] - 2025-12-11

### Added
-   **Documentation**: Added status badges (Version, License) and a direct "Live Demo" link to the `README.md`.

## [v1.7.3] - 2025-12-11

### Added
-   **Favicon**: Added a "Gift Box" (🎁) favicon to the application using an SVG data URI for instant visibility.

## [v1.7.2] - 2025-12-03

### Added
-   **License**: Added MIT License (Copyright (c) 2025 Kuan Cheen).
-   **Copyright Notice**: Added copyright header to `index.html` and `README.md`.

## [v1.7.1] - 2025-12-02

### Fixed
-   **Duplicate Handling**: Added logic to automatically filter out duplicate numbers when saving the "Number List" in settings.

## [v1.7.0] - 2025-12-01

### Changed
-   **Responsive Layout**: Updated prize box layout to use Flexbox with balanced row distribution.
    -   5 prizes now fit in a single row.
    -   6 prizes split into two rows of 3 (3+3).
    -   Overflow rows are centered for better visual balance.

## [v1.6.0] - 2025-12-01

### Added
-   **Sound Effects**: Added a drum roll sound effect that plays sequentially for each prize draw.
    -   Sound plays from 4.5s to 7s of the clip for a punchy effect.
    -   Supports concurrent playback for multiple prizes without cutting off.

## [v1.5.0] - 2025-11-26

### Added
-   **New Brand Theme**: Implemented "Where Wisdom Finds Peace" event branding.
    -   **Royal Blue Background**: Updated main background to deep blue (`#1a3ba0`) with starburst gradient.
    -   **Gold Accents**: Added gold borders, text gradients, and highlights (`#fbbf24`).
-   **Typography**:
    -   Added **'Kaushan Script'** for the main title to match the event visual.
    -   Added **'Poppins'** for body text and UI elements for a modern, clean look.
-   **UI Enhancements**:
    -   Updated "Start Draw" button to a Gold/Amber gradient.
    -   Refined "Glassmorphism" effects on panels to blend with the blue theme.
    -   Updated "Number Box" and "Flip Digit" styles to align with the new color palette.

### Changed
-   Updated `index.html` to include new Google Fonts (`Poppins`, `Kaushan Script`).
-   Refactored CSS variables and Tailwind classes to support the new theme.
