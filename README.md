# COMPX234 Lab 2: Readers-Writers Problem
## Monitor Implementation in Python
### Overview
This project implements the classic **Readers-Writers synchronization problem** using a monitor design pattern with Python's `threading` library.

### Key Rules Implemented
- Multiple readers can read at the same time when no writer is active.
- Writers have **exclusive access** to the shared resource.
- No race conditions or concurrent access violations.
- Prevents writer starvation.

### Files
- `readers_writers.py`: Complete implementation of the monitor, threads, and simulation.

### How to Run
```bash
python readers_writers.py