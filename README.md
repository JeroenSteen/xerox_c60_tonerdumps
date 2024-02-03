Xerox Colour C60 dump files created with Proxmark 3 RDV4
---

By sharing these dump files I hope to gain more knowledge about the contents of these chips. Please share your thoughts if you know more information.
The commando's that I used were: `hf xerox dump` and `hf xerox dump -d`.

Info blocks
---
0x15 (21), 0x16 (22), 0x17 (23), 0x18 (24), 0x22 (34)

|     |       |
|-----|-------|
| 0   | PartNo|
| 1   | PartNo|
| 2   | PartNo|
| 3   | PartNo|
| 4   | PartNo|
| 5   | PartNo|
| 6   | Type (Toner=14/Drum=11)|
| 7   | Type (Toner=14/Drum=11)|
| 8   | Date/Day|
| 9   | Date/Month|
| 10  | Date/Year|
| 11  | Type (Toner=0/Drum=1)|
| 12  | Serial|
| 13  | Serial|
| 14  | Serial|
| 15  | 255|
| 16  | 65|
| 17  | 0|
| 18  | Type (Toner/Drum, Proxmark-way to check)|
| 19  | 0|

Note: Serial being found is 8-digit, but Xerox Supply is 12-digit.

Var blocks
---
0x1c (28), 0x1e (30), 0x20 (32), 0x26 (38), 0x28 (40), 0x2a (42), 0x2c (44), 0x2e (46)

Secret blocks
---
0x1c (28), 0x1d (29), 0x1e (30), 0x1f (31), 0x20 (32), 0x21 (33), 0x26 (38), 0x27 (39), 0x28 (40), 0x29 (41), 0x2a (42), 0x2b (43), 0x2c (44), 0x2d (45), 0x2e (46), 0x2f (47)

