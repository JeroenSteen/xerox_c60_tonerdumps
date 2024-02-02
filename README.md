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
| 6   |       |
| 7   |       |
| 8   | Date  |
| 9   | Date  |
| 10  | Date  |
| 11  |       |
| 12  | Serial|
| 13  | Serial|
| 14  | Serial|
| 15  |       |
| 16  |       |
| 17  |       |
| 18  | Type  |
| 19  |       |

Var blocks
---
0x1c (), 0x1e (), 0x20 (), 0x26 (), 0x28 (), 0x2a (), 0x2c (), 0x2e ()

Secret blocks
---
(28), (29), (30), (31), (32), (33), (38), (39), (40), (41), (42), (43), (44), (45), (46), (47)

