## Contributors & Credits
This project was developed as a group assignment (4 members) at UCL. The other authors wish to remain anonymous.

**Laluke1**
*Persistence Engine:* Implemented file I/O to serialize and retrieve game state (Pet Name, Stats) from disk, enabling progress to be saved across sessions.
*Input Handling & Control Flow:* Built the user input logic to parse commands and map keystrokes to specific game actions (e.g., Feeding, Playing).
*Game Loop Logic:* Developed the "Offline Depletion" algorithm to calculate stat decay based on system time deltas since the last save.
*State Management:* Handled edge cases for corrupted/empty save files and implemented value clamping to ensure stats remain within logic boundaries.
