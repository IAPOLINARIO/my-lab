# Treasure Hunt

You're part of a pirate crew, and you've just discovered a map to hidden treasure! But beware; the treasure is guarded by traps. Use a WaitGroup to ensure that all pirates have a chance to grab their share before escaping the island.

- Constraints: Use goroutines and WaitGroups.
- Input: Pirates and their positions.
- Expected Output: All pirates get their share of the treasure.
- Learning: Understand how to use WaitGroups to wait for multiple goroutines.
- Benefits: Learn how to coordinate multiple tasks.
- Tips:
  1. Use a sync.WaitGroup to make sure all pirates get their share.
  2. Think about how to divide the treasure among pirates; maybe each pirate function could return its share through a channel.
  3. Use a separate goroutine to close the channel after all pirates have taken their share.
