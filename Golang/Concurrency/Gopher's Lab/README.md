# Gopher's Lab: The Files of Destiny

Dr. Gopherstein needs to decipher ancient manuscripts (files) to find the cure for a dreadful disease. The clock is ticking, and patients are waiting! Use goroutines to read these large files concurrently and find the word count to create the antidote formula.

- Constraints: Use goroutines and channels. Mock the file reading. Should not take longer than 2 seconds.
- Input: Mocked content of 3 large manuscripts.
- Expected Output: Word count from each manuscript to make the cure.
- Learning: Understand how to perform I/O-bound operations concurrently.
- Benefits: Save lives by speeding up I/O operations. Literally!
- Tips:
  1. Think about using goroutines to handle file read and write operations concurrently.
  2. Use channels to signal when a file operation is complete or if an error occurs.
  3. Experiment with buffered channels if you're dealing with a lot of files, as this can help manage back pressure.
  4. You might find sync.Once useful for initializing shared resources, like a file that multiple goroutines write to.
