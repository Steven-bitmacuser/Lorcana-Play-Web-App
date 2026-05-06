# Lorcana VTT (Virtual Tabletop)

A lightweight, multiplayer virtual tabletop designed specifically for playing Lorcana with friends. No setup required, just share a link and play.

## 🚀 Getting Started

### Quick Start (Development)
1. **Install Dependencies**
   ```bash
   npm install
   ```
2. **Launch Application**
   ```bash
   npm run dev
   ```
3. **Open in Browser**
   Navigate to `http://localhost:3000`.

## 🎮 How to Play

### 1. Multiplayer Sync
* To play with a friend, simply ensure you are both in the same **Room** (set in the sidebar). 
* Share the URL with the `?room=YOUR_ROOM_NAME` parameter to join automatically.

### 2. Choosing Roles
* **P1 (Bottom):** Spawns your hand at the bottom of the table.
* **P2 (Top):** Spawns your hand at the top.
* **Spectator:** Watch the game without any interaction permissions.

### 3. Importing a Deck
* Visit [Dreamborn.io](https://dreamborn.io) and export your deck as "JSON (Tabletop Simulator)".
* Paste the JSON code into the **Import Deck** box in the sidebar.
* The application will automatically download the card images and populate your deck.

### 4. Controls
* **Left Click + Drag:** Move cards.
* **Right Click:** Exhaust/Ready (Rotate 90°).
* **Double Click:** Flip face up/down.
* **Bottom-Right Corner Drag:** Resize card (maintains aspect ratio).
* **Delete Button (Hover):** Removes card and returns it to your deck.
* **Inkwell Zone:** Dragging a card into the horizontal "Inkwell" strips will automatically flip it face down and mark it as Ink.
* **Drawing Mode:** Toggle the brush icon to draw damage markers or arrows directly on the board.

## 🛠 Tech Stack
* **Frontend:** React + Tailwind CSS + Framer Motion
* **Backend:** Node.js + Express + Socket.io
* **Build Tool:** Vite

## ⚖️ Disclaimer
This is an unofficial fan project and is not affiliated with Disney or Ravensburger. All card images and Lorcana intellectual property belong to their respective owners.
