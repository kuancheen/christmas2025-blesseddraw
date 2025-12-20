# Blessed Draw App (v2.1.2)
![Version](https://img.shields.io/badge/version-v2.1.2-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Semantic Versioning](https://img.shields.io/badge/semver-2.0.0-blue)
![Status](https://img.shields.io/badge/status-active-success)
![Hits](https://hits.sh/github.com/kuancheen/christmas2025-blesseddraw.svg?view=today-total&style=flat&label=👁️%20Views&extraCount=0&color=6366f1)
[![Live Demo](https://img.shields.io/badge/demo-online-orange)](https://kuancheen.github.io/christmas2025-blesseddraw/)

🔗 **Live Demo**: [Click Here to Run App](https://kuancheen.github.io/christmas2025-blesseddraw/)

This is a premium, self-contained web application designed for real-time, non-repeating number draws. Featuring a vibrant **Royal Blue and Gold** theme, it uses local storage for persistence and provides a smooth, state-of-the-art jackpot experience.

## 1. Running the App
Simply open the `index.html` file in any modern web browser (Chrome, Edge, Safari, etc.).

## 2. Managing Data & Settings
The app uses your browser's local storage for data persistence, simulating a connected database.

1.  **Access Settings:** Click the **Settings** button (⚙️) next to "Start Draw."
2.  **Prize Count:** Adjust the number of active prize boxes (between `1` and `20`) in the "Number of Prizes" field.
3.  **Import Numbers:**
    * Open your source spreadsheet (e.g., Google Sheet).
    * Copy the column of unique numbers you want to draw from.
    * Paste the numbers (one per line) into the large text area under "Number List." (Duplicates are automatically removed).
4.  Click **Save Changes**.

> **Note:** The app remembers your list and which numbers have been drawn even if you close the browser, as long as you don't clear your browser cache.

## 3. Managing Prize Status & Draw History

You can control the status of prizes using two methods:

### A. Toggling Prize Boxes (Interactive)
The main prize boxes and the header are interactive:
1.  **Box Toggle**: Click directly on any **Prize Box** to cycle its status: `Active` → `Disabled` → `Claimed`.
2.  **Draw Trigger**: Click the **"Blessed Draw"** title header to trigger a draw (same as clicking "Start Draw").

### B. Prize Status Settings (Manual)
1.  Locate the "Active Prizes" section above the settings button.
2.  Click the corresponding button (e.g., "`Prize 3 (Active)`").
3.  The button will change to "`Disabled`," and the main prize box will turn gray. Click again to change to "`Claimed`" or re-activate.

### B. Claiming Drawn Numbers (After Draw)
Once a number is drawn, you manage its claim status in the **Draw History** section:
1.  Find the entry in the list (e.g., "`0872 Prize 5...`").
2.  If the status is "`Unclaimed`," click the **Claim** button next to it.
3.  This marks the prize as "`Claimed`" (red status) and visually updates the main prize box, confirming the winner is processed.
4.  Click **Unclaim** to reverse this status.

## 4. Drawing Numbers
1.  Ensure you have enough numbers loaded and at least one prize box is set to "`Active`."
2.  Click the large **Start Draw** button.
3.  The active boxes will spin and reveal random, **unique** numbers from your available list.
4.  The drawn numbers are automatically marked as "`Drawn`" internally so they cannot be picked again.

## 5. Exporting Results
You can easily save or share your draw history:
1.  **Copy to Clipboard**: Click the **Copy** button in the "Draw History" section to copy the formatted text.
2.  **CSV Download**: Click the **Download CSV** button to export your results for spreadsheet use.
3.  **Notifications**: A theme-consistent modal will confirm your actions (e.g., "History Copied!").

## 6. Sound Effects
-   A high-quality **drum roll** sound plays sequentially for each prize draw.
-   The sound is perfectly synchronized with each box's animation for maximum impact.
-   **Note**: Ensure your device volume is on. Browsers may require an initial click (like "Start Draw") to enable audio.

## 6. Key Features
- **Interactive Triggers**: Both the main title and individual prize boxes are interactive. Click the title to start a draw, or click a prize box to toggle its status.
- **Data Export**: Easily copy the entire draw history to your clipboard or download it as a CSV file for record-keeping.
- **Increased Capacity**: Supports up to 20 simultaneous jackpot prizes for larger events.
- **Theme-Consistent UI**: Enhanced with custom notification modals and a glassmorphism design that scales beautifully.
- **Cache Busting**: Integrated versioning for internal assets ensure you always have the latest features and bug fixes.

## 7. License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Copyright (c) 2025 Kuan Cheen.

