# The Grand Race: Tortoise and the Hare

The grand race between the Tortoise and the Hare is about to begin! Each contender is represented by a function that prints its progress at intervals. Make the race fair by using goroutines and timers to ensure that each contender has an equal chance to win!

- Constraints: Use goroutines, timers, and channels.
- Input: A distance for the race (e.g., 10 "steps").
- Expected Output: Who wins the race!
- Learning: Master the use of timers in goroutines.
- Benefits: Understand how to manage time-sensitive operations concurrently.
- Tips:
  1. Use time.Sleep() to simulate each contender's speed.
  2. Use a channel to signal the end of the race and declare a winner.
  3. Experiment with time.Ticker for periodic updates on the race status.
