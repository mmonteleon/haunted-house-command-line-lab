# 🏰 Haunted House Terminal Quest (Deep Mansion Edition)

Welcome, Investigator! You are trapped inside a haunted mansion filled with hidden passages, deep closets, drawers, and locked trunks.

To break the curse and escape, you must navigate deeper into nested directories, inspect hidden files, search logs, and move artifacts across the house.

---

## 📜 Navigation Tips for Multi-Level Directories
- `pwd` — Shows your current exact path in the mansion
- `ls` — Look around the current directory
- `ls -a` — Find hidden files (`.` files)
- `cd <folder>` — Move deeper into a room or item
- `cd ..` — Move up one directory level
- `cd ../..` — Move up two directory levels
- `cat <file>` — Read a file or clue
- `grep <word> <file>` — Search inside a file for a word
- `mv <source> <destination>` — Move or rename an item
- `rm <file>` — Delete/destroy cursed items

---

## 🎯 Goal
1. Locate the **silver_key** hidden deep inside the kitchen pantry (`kitchen/pantry/dark_corner/`) and move it back to `foyer/`.
2. Locate and delete (`rm`) both **curse_scroll.txt** (`attic/old_trunk/bottom_layer/`) and **poison_ivy.txt** (`conservatory/greenhouse/`).
3. Unlock the chest inside `basement/storage_rack/` by renaming `.padlock_LOCKED` to `.padlock_UNLOCKED`.
4. Read all `.clue` files along the way!

Start exploring by entering rooms: `cd library`, `cd kitchen`, etc.
