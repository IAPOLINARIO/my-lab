# The Night Watch

The night is dark and full of terrors. As a member of the Night's Watch, your task is to keep an eye out for incoming threats. Use tickers to simulate periodic checks and alerts.

- Constraints: Use goroutines and tickers.
- Input: Time intervals for periodic checks.
- Expected Output: Alerts at each time interval.
- Learning: Get to grips with tickers for periodic tasks.
- Benefits: Learn how to handle repetitive tasks in a concurrent manner.
- Tips:
  1. Utilize time.NewTicker to create a new ticker for periodic checks.
  2. Use a channel to receive 'ticks' from the ticker and trigger the alert.
  3. Consider adding another channel to stop the ticker after a certain period or condition.
