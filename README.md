# CharWeb

Map relationships between characters. No installation, no account — everything is stored locally in your browser.

**[→ Open CharWeb](https://starman404.github.io/ocs_relationship_chart/)**

---

## Core Concepts

**Characters** are nodes on the canvas. **Images** are free-floating pictures you can place anywhere. Both live on a shared **Layers** panel where you can control their stacking order. **Links** are the lines connecting characters, each typed with a relationship label and optional arrow direction.

All your work is organised into **Charts** (individual webs) which can be grouped into **Folders** inside the **Library** panel on the left.

---

## The Interface

| Area | What it does |
|---|---|
| **Top bar** | Mode toggle, add buttons, view options, save/export |
| **Library** (left) | Charts and folders — your project browser |
| **Canvas** (centre) | The interactive relationship map |
| **Layers / Sidebar** (right) | Relationship types, filters, and the layer stack |

### Modes

- **Edit mode** — create, move, connect, and delete everything
- **View mode** — click a character to highlight only their connections; everything else fades

---

## Characters

**Add a character** — click **＋ Character** in the top bar. You can give them a name, a profile photo, and a coloured border.

**Move** — drag the node anywhere on the canvas.

**Edit / Delete / Lock** — hover over a node to reveal three buttons directly on it: ✎ edit, 🔒 lock/unlock, ✕ delete.

**Connect two characters** — in Edit mode, hover a node to reveal the small dots around its edge. Drag from any dot to another character to create a link.

---

## Links

Dragging from one character to another opens the **link modal**. Here you can:

- Toggle one or more **relationship types** on or off
- Set an **arrow direction** for each type (none, →, ←)

Double-click any link line to re-open the modal and edit it. Drag the midpoint handle to curve the line. Drag the anchor dots at either end to reposition where the line attaches.

---

## Relationship Types

The sidebar lists all relationship types for the current chart. Click **+** to add a new one — give it a name and a colour. Hover any type to rename or delete it.

In **View mode**, use the **Filter Relationships** section to show or hide specific types.

---

## Images

**Add an image** — click **🖼 Image** in the top bar and pick a file. PNG transparency is preserved.

**Move** — drag the image on the canvas.

**Resize** — click the image to select it, then drag any corner handle.

**Edit** — double-click to open the edit panel where you can set exact dimensions, lock the aspect ratio, and adjust border radius.

**Delete** — open the edit panel and click Delete, or select the image and press `Delete`.

Images appear in the **Layers** panel alongside characters and can be reordered freely by dragging.

---

## Layers Panel

The **Layers** panel (bottom of the right sidebar) shows every character and image in the chart, ordered from top (front) to bottom (back).

- **Drag rows** to change the stacking order on the canvas
- **Click a row** to select that item
- **Lock / Edit / Delete** buttons appear on hover
- **Groups** appear as named folders (see Groups below)

---

## Selection & Multi-Select

| Action | Result |
|---|---|
| Click a character or image | Select it |
| `Ctrl+click` | Add to / remove from selection |
| `Ctrl+drag` on empty canvas | Draw a selection rectangle |
| `Ctrl+A` | Select everything |
| `Escape` | Deselect all |

When 2 or more items are selected a bounding box appears. You can drag any selected item to move the whole selection together.

---

## Groups

Groups let items move together as a unit.

**Create a group** — select 2 or more items, then press `Ctrl+G` or click **⊞ Group** in the Layers panel action bar.

**Select a group** — click any member; the whole group is selected automatically.

**Move a group** — drag any member; the rest follow silently.

**Rename a group** — double-click the group's folder name in the Layers panel and type a new name.

**Ungroup** — select any group member and press `Ctrl+G` again, or click **⊟ Ungroup** in the action bar or on the folder row.

---

## Locking

Lock any item to prevent accidental moves. Locked items show a 🔒 icon in Edit mode.

| Method | How |
|---|---|
| Single item | Hover the node → click 🔒, or use the lock button in the Layers panel |
| Selection | `Ctrl+L` |

---

## Copy & Paste

`Ctrl+C` copies the current selection (characters, images, and any links between copied characters). `Ctrl+V` pastes a duplicate with a 20 px offset. Pasted items are automatically selected so you can move them immediately.

---

## Layout & View

- **⊙ Circle** — auto-arranges all unlocked characters in a circle. Locked characters stay put.
- **⤢ Fit** — zooms and pans to fit everything on screen
- **🏷 Names** — toggles character name labels on/off
- Scroll to zoom, middle-click-drag or click-drag on empty canvas to pan

---

## Saving & The Library

Work is auto-saved every 30 seconds. To save manually press `Ctrl+S` or click **💾 Save**.

The **Library** panel manages multiple charts:

- **+ Chart** — create a new blank chart
- **+ Folder** — organise charts into folders
- Click any chart to open it
- Hover a chart or folder for rename, duplicate, and delete options
- Drag charts into folders

---

## Export & Import

| Button | What it exports |
|---|---|
| **↑ Export** (top bar) | The current chart as a `.json` file |
| **↑ Export All** (library footer) | Your entire library as a single `.json` |
| **↓ Import** (top bar) | Import a single chart `.json` |
| **↓ Import** (library footer) | Merge a full library export |

Folders can also be exported individually from the library (hover a folder → export icon).

---

## Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl+Z` | Undo |
| `Ctrl+Y` / `Ctrl+Shift+Z` | Redo |
| `Ctrl+C` | Copy selection |
| `Ctrl+V` | Paste |
| `Ctrl+G` | Group / Ungroup |
| `Ctrl+L` | Lock / Unlock selection |
| `Ctrl+A` | Select all |
| `Delete` / `Backspace` | Delete selection |
| `Escape` | Deselect all |

---

## Tips

- Hold `Ctrl` while clicking multiple items to build a selection before grouping or moving them together.
- Use **lock** to freeze background images or decorative elements so they don't move while you work on the characters.
- The stacking order in the Layers panel matters for overlapping images — drag them to control what appears in front.
- Charts auto-save whenever you switch between them in the Library.
