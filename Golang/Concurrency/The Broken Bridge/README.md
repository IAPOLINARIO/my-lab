# The Broken Bridge

A bridge can only hold 3 gophers at a time, and they can only cross if they're going in the same direction. Use channels to ensure safe passage for all the gophers.

- Constraints: Use channels and goroutines.
- Input: A list of gophers and their desired direction.
- Expected Output: All gophers cross safely.
- Learning: Get hands-on experience with buffered channels.
- Benefits: Learn to manage resource access with buffered channels.
- Tips:
  1. Use a buffered channel to limit the number of gophers on the bridge.
  2. Use another channel to communicate the direction the gophers are traveling in.
  3. Consider using select to handle multiple channels if you include a way to abort the crossing.
