
### 🔎 Overview
This folder contains demonstrations of Python thread synchronization primitives applied to the **same CPU-bound** workload: matrix multiplication implemented in `matrix_mul.py`. Each `*_test.py` file shows one synchronization primitive in a clear, small example that runs a number of worker threads calling `do_something(count)` from `matrix_mul.py`.

**Concepts covered**
- `Barrier` — synchronize start of threads  
- `Condition` — notify/wait pattern for controller/producer  
- `Event` — signal threads to start simultaneously  
- `Semaphore` — limit concurrent workers  
- `Lock` — protect shared data (critical section)  
- `RLock` — recursive lock (same thread re-acquires lock)  
- `Queue` — producer-consumer pattern (thread-safe queue)

---

### 🧩 How to run (Windows / macOS / Linux)
1. Open a terminal (PowerShell, Command Prompt, or macOS/Linux terminal).  
2. `cd` into the task folder:

```bash
cd "E:\Fizza\Univershitty\Sixth semester\PDC\CHAPTER_2\Task_2"
git