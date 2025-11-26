# Blessed Draw App (v1.5.0)

This is a self-contained web application designed to facilitate real-time, non-repeating number draws for jackpot prizes. It runs entirely in your browser using local storage for persistence.

## 1. Running the App
Simply open the `index.html` file in any modern web browser (Chrome, Edge, Safari, etc.).

## 2. Managing Data & Settings
The app uses your browser's local storage for data persistence, simulating a connected database.

1.  **Access Settings:** Click the **Settings** button (⚙️) next to "Start Draw."
2.  **Prize Count:** Adjust the number of active prize boxes (between `1` and `10`) in the "Number of Prizes" field.
3.  **Import Numbers:**
    * Open your source spreadsheet (e.g., Google Sheet).
    * Copy the column of unique numbers you want to draw from.
    * Paste the numbers (one per line) into the large text area under "Number List."
4.  Click **Save Changes**.

> **Note:** The app remembers your list and which numbers have been drawn even if you close the browser, as long as you don't clear your browser cache.

## 3. Managing Prize Status & Draw History

You can control the status of prizes using two methods:

### A. Disabling Prizes (Before Draw)
If you need to temporarily skip a prize box for the next draw:
1.  Locate the "Active Prizes" section above the settings button.
2.  Click the corresponding button (e.g., "`Prize 3 (Active)`").
3.  The button will change to "`Disabled`," and the main prize box will turn gray, ensuring it is not included in the draw. Click it again to re-activate it.

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
