# The Chronicles of Gopherland: The Sum of All Fears

In the mystical kingdom of Gopherland, a dark wizard named Mutexo has risen to power. He's discovered an ancient spell that will shroud the world in eternal darkness.
However, the spell is powered by a magical array, and the only way to stop it is by finding the sum of that array before the last leaf of the Elder Tree falls.

- Constraints: Use goroutines and channels. Should not take longer than 1 second.
- Input: A magical array of integers [1, 2, 3, 4, 5, 6, 7, 8, 9]
- Expected Output: The sum that can defeat the wizard.
- Learning: Master basic usage of goroutines and channels for parallel computation.
- Benefits: Learn to break down problems and solve them faster than a wizard's spell.

- Tips
  1. Use a fan-out pattern where one goroutine generates jobs and multiple worker goroutines perform the tasks.
  2. Use one channel for sending jobs to workers and another for collecting results.
  3. To maintain order, consider using an identifier for each job and sort the results based on this identifier.
  4. Experiment with sync.WaitGroup to ensure all worker goroutines complete their tasks before you collect all results.
