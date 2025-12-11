# Changelog

All notable changes to this project will be documented in this file.

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
