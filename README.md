# How to Install a Bookmarklet

A **bookmarklet** is a browser bookmark that runs JavaScript on the page you are viewing instead of opening a new site.

---

## 1. Requirements

- A JavaScript snippet that starts with `javascript:` (for example: `javascript:alert('Hello!');`)
- A visible bookmarks/favorites bar in your browser so you can click the bookmarklet easily.

---

## 2. Universal Installation Steps (Desktop Browsers)

These steps work in Chrome, Firefox, Edge, Brave, and most Chromium-based browsers.

1. **Show the bookmarks bar**  
   - Use `Ctrl+Shift+B` (Windows/Linux) or `Cmd+Shift+B` (macOS) in most browsers.

2. **Create a new bookmark**  
   - Right‑click the bookmarks bar and choose “Add page…” / “Add bookmark…”.

3. **Name the bookmarklet**  
   - Pick something short and clear, e.g. `Pinker`, `Toggle Dark Mode`, `Word Counter`.

4. **Paste the JavaScript code as the URL**  
   - In the **URL/Location** field, paste your code starting with `javascript:`.

5. **Save the bookmark**  
   - Confirm/Save; the new item appears on the bookmarks bar.

6. **Use the bookmarklet**  
   - Open any page, then click the bookmarklet; it will run its JavaScript on the current page.

---

## 3. Browser-Specific Notes

### Chrome (Desktop)

1. Toggle bookmarks bar: `Ctrl+Shift+B` / `Cmd+Shift+B`.
2. Right‑click the bar → “Add page…”.
3. Enter a name and paste the `javascript:...` code into the URL field.
4. Click “Save”. The bookmarklet appears on the bar.

### Firefox (Desktop)

1. Show the Bookmarks Toolbar (View → Toolbars → Bookmarks Toolbar, or via settings).
2. Right‑click the toolbar → “New Bookmark…”.
3. Set a name, paste the `javascript:...` code into the Location field, and save.

### Microsoft Edge (Chromium)

1. Show the favorites bar from the Edge settings menu.
2. Add any favorite to the bar, then right‑click it → “Edit”.
3. Replace the URL with your bookmarklet `javascript:...` code and save.

### Safari (macOS)

1. Enable Favorites Bar (View → Show Favorites Bar).
2. Add a bookmark (Bookmarks → Add Bookmark…).
3. Name it, paste your `javascript:...` code into the Address field, then save.

> Mobile browsers often restrict bookmarklets; iOS/Android usually require creating a normal bookmark, then editing its URL to the `javascript:...` code.

---

## 4. Example Bookmarklet for Testing

Use this minimal example to verify that installation works:

```text
javascript:(function () {
  alert('Bookmarklet works!');
})();
