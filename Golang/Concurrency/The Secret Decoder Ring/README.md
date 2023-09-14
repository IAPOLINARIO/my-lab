# The Secret Decoder Ring

You've intercepted a message from enemy spies, but it's encrypted. Multiple cyphers are needed to decode it. Use a fan-in pattern to collect all the decoded messages into one channel.

- Constraints: Use goroutines, channels, and the fan-in pattern.
- Input: Multiple encrypted messages.
- Expected Output: One decoded message.
- Learning: Master the fan-in concurrency pattern.
- Benefits: Learn how to merge multiple channels into one.
- Tips:
  - Create separate goroutines for each slice of the message to be decoded, making the operation concurrent.
  - Use channels to collect the decoded slices. This will ensure you're gathering the results as they come in.
  - Since you'll be working with multiple outputs, consider implementing a fan-in function that takes multiple channels as inputs and consolidates them into a single channel.
  - Keep an eye on the order of your decoded slices. You might need to sort them to reconstruct the original message properly.
