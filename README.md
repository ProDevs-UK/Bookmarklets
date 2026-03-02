# How to Install a Bookmarklet

A **bookmarklet** is a browser bookmark that runs JavaScript on the page you are viewing instead of opening a new site.[web:6][web:15]

---

## 1. Requirements

- A JavaScript snippet that starts with `javascript:` (for example: `javascript:alert('Hello!');`).[web:6][web:7]  
- A visible bookmarks/favorites bar in your browser so you can click the bookmarklet easily.[web:11][web:13]

---

## 2. Universal Installation Steps (Desktop Browsers)

These steps work in Chrome, Firefox, Edge, Brave, and most Chromium-based browsers.[web:3][web:6]

1. **Show the bookmarks bar**  
   - Use `Ctrl+Shift+B` (Windows/Linux) or `Cmd+Shift+B` (macOS) in most browsers.[web:11]

2. **Create a new bookmark**  
   - Right‑click the bookmarks bar and choose “Add page…” / “Add bookmark…”.[web:7][web:11]

3. **Name the bookmarklet**  
   - Pick something short and clear, e.g. `Pinker`, `Toggle Dark Mode`, `Word Counter`.[web:7][web:14]

4. **Paste the JavaScript code as the URL**  
   - In the **URL/Location** field, paste your code starting with `javascript:`.[web:6][web:7][web:13]

5. **Save the bookmark**  
   - Confirm/Save; the new item appears on the bookmarks bar.[web:7][web:13]

6. **Use the bookmarklet**  
   - Open any page, then click the bookmarklet; it will run its JavaScript on the current page.[web:3][web:6]

---

## 3. Browser-Specific Notes

### Chrome (Desktop)

1. Toggle bookmarks bar: `Ctrl+Shift+B` / `Cmd+Shift+B`.[web:11]  
2. Right‑click the bar → “Add page…”.[web:7][web:11]  
3. Enter a name and paste the `javascript:...` code into the URL field.[web:6][web:7]  
4. Click “Save”. The bookmarklet appears on the bar.[web:7]

### Firefox (Desktop)

1. Show the Bookmarks Toolbar (View → Toolbars → Bookmarks Toolbar, or via settings).[web:3][web:8]  
2. Right‑click the toolbar → “New Bookmark…”.[web:7]  
3. Set a name, paste the `javascript:...` code into the Location field, and save.[web:6][web:7]

### Microsoft Edge (Chromium)

1. Show the favorites bar from the Edge settings menu.[web:2][web:5]  
2. Add any favorite to the bar, then right‑click it → “Edit”.[web:5][web:13]  
3. Replace the URL with your bookmarklet `javascript:...` code and save.[web:5][web:13]

### Safari (macOS)

1. Enable Favorites Bar (View → Show Favorites Bar).[web:3]  
2. Add a bookmark (Bookmarks → Add Bookmark…).[web:3]  
3. Name it, paste your `javascript:...` code into the Address field, then save.[web:6]

> Mobile browsers often restrict bookmarklets; iOS/Android usually require creating a normal bookmark, then editing its URL to the `javascript:...` code.[web:6][web:8]

---

## 4. Example Bookmarklet for Testing

Use this minimal example to verify that installation works:[web:6][web:7]

```text
javascript:(function () {
  alert('Bookmarklet works!');
})();
