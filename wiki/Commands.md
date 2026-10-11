# Commands

Fungal Rebirth adds one command, used to find the [Pile of Rotten Logs](Pile-of-Rotten-Logs.md) structures.

---

## /fungalrebirth locatepile

| | |
|---|---|
| **Syntax** | `/fungalrebirth locatepile` |
| **Permission level** | 2 (operator) |
| **Dimension searched** | Overworld |

Shows the coordinates and distance of the **nearest Pile of Rotten Logs that has already been placed** in the world.

### Output

| Result | Message |
|---|---|
| Success | *Nearest Pile of Rotten Logs: X Y Z (N blocks)* |
| No pile placed yet | *No Pile of Rotten Logs has been placed yet (explore the Ancient Forest).* |

### Notes

- Piles are only placed after their area has been generated and loaded, so the command only finds piles in parts of the world that have already been explored. It does not search ungenerated terrain like `/locate`.
- The distance is measured from where the command is run.
- The messages are translated into the player's language when a translation is available (English and Brazilian Portuguese are included).

---

## See Also

- [Pile of Rotten Logs](Pile-of-Rotten-Logs.md)
- [Home](Home.md)
