# The Philosopher's Dinner

Five philosophers are sitting around a circular table. Each philosopher thinks deeply and occasionally interrupts his musings to grab two forks and eat from a bowl of spaghetti. Use mutexes to prevent more than one philosopher from holding a given fork at a time.

- Constraints: Use goroutines and mutexes.
- Input: Philosophers and their forks.
- Expected Output: A deadlock-free dinner.
- Learning: Understand how to use mutexes to control access to shared resources.
- Benefits: Learn to solve classic concurrency problems.
- Tips:
  1. Use a mutex for each fork to simulate a philosopher picking it up and putting it down.
  2. Consider using sync.Mutex's Lock() and Unlock() methods.
  3. Pay attention to deadlock scenarios. Maybe let philosophers release their forks if they can't acquire both.
