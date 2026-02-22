# Shot Tracker — User Guide

---

## What This App Does

Shot Tracker is a GPS-based golf shot tracking app for iPhone. It records every shot you hit, tracks where your ball lands using GPS, tells you the distance to the flag, and generates a full round report when you're done. Everything is stored on your phone — no account, no internet required on the course.

---

## First Time Setup

Before playing your first round you need two things: a **bag** and a **course**.

### Create a Bag

A bag stores your club carry and total distances. The app uses these to suggest the right club when you're on the course.

1. Tap **📚** (Library) in the top-right header
2. Tap **+ New Bag** in the Bag Library section
3. Give your bag a name (e.g. "My Bag")
4. Tap **Activate** on the new bag card to make it the active bag
5. Close the Library and tap the **🏌️ bag icon** in the header to open the Bag Editor
6. Select a club and shot type from the dropdowns, enter Carry and Total distances, tap **Save to Bag**
7. Repeat for each club and shot type combination
8. Tap **Manage Clubs** if you need to add custom clubs or shot types beyond the defaults

Distances are in yards. Putts are entered in feet.

### Create a Course

A course stores hole-by-hole par, yardage, and handicap. GPS tee and flag positions are saved automatically as you play.

1. Tap **📚** (Library), then **+ New Course**
2. Give the course a name
3. Tap **Activate** on the course card
4. Close — you can fill in par/yards/hcp during the round via the **⚙️ Course Setup** screen (gear icon in header), or before you play if you know the details

---

## Starting a Round

1. Tap **🔄** (New Round) in the header
2. Select your bag and course from the dropdowns
3. Tap **Start Round**

If you have shots recorded from a previous session you'll be asked to confirm clearing them first.

---

## On the Course — Hole by Hole

### The Main Screen

The main screen has two sections:

**Rangefinder** — GPS distance to the flag, target entry, and the main action buttons  
**Shots** — the running list of every shot recorded on the current hole

The **scoreboard** at the top shows your current hole, par, score for this hole, total shots, and cumulative vs par.

---

### Step 1 — Mark the Tee

When you arrive at the tee, tap **Tee**. This saves your GPS position as the tee for this hole. You only need to do this once per hole. The app will warn you if you try to move the tee after recording shots.

### Step 2 — Mark the Flag

Walk up to the pin and tap **Flag**. This saves the GPS position of the hole. Once both tee and flag are set, the **To Flag** distance display will start showing your live GPS distance to the flag, updating as you move.

Both tee and flag positions are saved permanently to your course library — you only need to set them once per hole on each course.

---

### Step 3 — Record a Shot

Before you hit, tap **Shot**. This records the shot and creates a pending marker (shown as ⏳ in the shot list). The **📍 Mark** button turns amber to indicate a shot is waiting to be located.

Select the club and shot type from the dropdowns in the shot row, or use Caddy (see below) to choose before recording.

**Target field** — optionally enter the distance you're aiming for before tapping Shot. This gets saved with the shot.

---

### Step 4 — Mark Where the Ball Landed

Walk to your ball. Tap **📍 Mark**. This saves your current GPS position as the landing spot for the most recent unlocated shot. The ⏳ changes to 📍 and the distance is calculated automatically.

If you hit multiple shots before marking (e.g. playing quickly), the app marks them in order — oldest first (FIFO). Keep walking to each ball and tapping Mark until all pending shots are located.

---

### Changing Holes

Tap **Hole ▶** to advance to the next hole, or **◀ Hole** to go back. Tap the blue **Hole** button in the middle to open the hole picker and jump directly to any hole.

---

## Caddy

Caddy suggests which club to use based on the distance you want to hit.

1. Enter a distance in the **Target** field on the main screen, or let it auto-fill from the To Flag distance
2. Tap **Caddy**
3. The sheet shows clubs within 10 yards of your target (tap **Within 10 / Show All** to toggle)
4. Tap **Carry / Total** to switch between carry and total distance mode
5. Tap **Select** next to a club to record that shot and close Caddy automatically

---

## Shot List Controls

Each shot row in the Shots section shows the club, shot type, distance, and GPS status. You can tap the distance to edit it directly.

**Pen** — marks the most recent shot as a penalty stroke (shown in red). Tap again to remove the penalty.

**Del** — deletes the most recent shot. Useful if you accidentally tapped Shot.

**Fwy** — manual fairway toggle. Tap to indicate you hit the fairway on this hole. Used in the round report stats. Only relevant on par 4s and par 5s.

**GIR** — green in regulation indicator. This is calculated automatically from your shot data — it lights up green when you've reached the green in the regulation number of shots (par minus 2). It dims when you've missed GIR, and stays neutral grey until you record your first putt on the hole. You don't need to tap it.

---

## Putts

Record putts the same way as any other shot. Select **PT** as the club and **putt** as the shot type. Enter the putt distance in **feet**. The app counts your putts automatically for the scorecard and report.

---

## Scorecard

Tap **📋** in the header to open the in-round scorecard. It shows all 18 holes with your score, par, and vs-par for each hole using standard golf notation:

- Double circle — eagle or better
- Single circle — birdie
- Plain number — par
- Single box — bogey
- Double box — double bogey
- Double box + (+) — triple bogey or worse

Front 9, back 9, and total are shown at the bottom. Tap Close to return to the main screen.

---

## Course Setup

Tap the **⚙️ gear icon** in the header to open Course Setup. Here you can enter or edit par, yardage, and handicap for each of the 18 holes. Tap Save when done. These values feed the scorecard, GIR calculation, and round report.

You can also switch which course is active from this screen using the course name field and the **▼** picker button.

---

## Round Report and Export

Tap **📊** in the header to open the Export sheet. Two options:

**⬇️ Download CSV** — saves a spreadsheet file to your phone. Opens with Numbers, Excel, or Google Sheets. Contains a round summary section at the top and a full shot-by-shot detail table below, including club, type, distance (with unit — ft for putts, y for everything else), bag carry/total, penalty flag, GPS coordinates, and timestamp.

**📄 View Report** — opens a formatted on-screen report with:
- Round summary (score, vs par, front/back 9)
- Key statistics (fairways, GIR, scrambling, putts, putt distances)
- Putting breakdown (0-putt through 4-putt+ counts)
- Holes by performance (grouped by eagle/birdie/par/bogey etc.)
- Score impact table (all holes sorted best to worst)
- Club performance (average distance vs bag carry, per club and shot type)
- Hole-by-hole detail (shots, clubs, distances, GPS, penalties)

Tap **📤 Share** at the top of the report to send a plain-text version via Messages, Mail, Notes, or any other app.

---

## Library

Tap **📚** in the header to open the Library. This is where you manage your bags and courses.

### Bag Library

Each bag card shows the bag name, number of club/type distance entries, and when it was created. Each card has five action buttons:

- **Activate** — makes this the active bag for the current round
- **Copy** — duplicates the bag with a new name (useful for creating a variation, e.g. wet weather distances)
- **Rename** — renames the bag
- **Delete** — permanently removes the bag (blocked if it's currently active)
- **Export** — saves this single bag as a JSON file

### Course Library

Same structure as bags. Each course shows the name, how many holes have tee GPS and flag GPS recorded, and created date. The same five actions apply.

### Import / Export

**Import Bag / Import Course** — opens the file picker. Select a JSON file exported from this app on another device. Duplicate items (matched by ID) are skipped automatically.

**Export All Bags / Export All Courses** — saves all bags or all courses as a single JSON file. Use this to transfer your full library to another phone.

### Full Backup

**💾 Backup All** — saves everything in one file: all bags, all courses, and the current round in progress. Do this regularly and before any phone upgrade.

**📂 Restore Backup** — confirms before proceeding, then restores all data from a backup file. This replaces everything currently on the device.

---

## New Round

Tap **🔄** in the header or **New Round** in the Library to start a new round. Select the bag and course to use, then tap **Start Round**. The hole index resets to hole 1 and the shot history is cleared.

---

## Tips for a Smooth Round

- **Set tee and flag GPS once** — positions are saved to the course permanently. On your second round at the same course the distances will show immediately.
- **Record Shot before you hit** — that's the intended flow. Tap Shot, hit the ball, walk to it, tap Mark.
- **Use Walk & Mark if playing quickly** — tap Shot for each player's ball, then walk and Mark each one in turn. The app always marks the oldest pending shot first.
- **Caddy auto-fills from GPS** — if the flag is set, the Target field pre-fills with the To Flag distance when you open Caddy. You can override it if you're laying up.
- **Back up before a round** — tap Library → 💾 Backup All. Takes two seconds and protects everything.

---

## Bag Editor (in-round)

The Bag Editor (tap the 🏌️ bag icon) lets you update club distances while you're on the course. If you're hitting your 7-iron further than your bag says, update it here and your caddy suggestions will improve immediately.

Select Club + Shot Type, enter the new Carry and Total, tap **Save to Bag**. The distance saves permanently to your bag library.

Tap **Manage Clubs** to add or remove clubs and shot types from the list.

---

*Shot Tracker v40.20*
