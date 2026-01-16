# Rate Limits

OutreachGuy enforces rate limits to keep your X account safe. These limits prevent actions that could trigger X's spam detection systems.

## Why rate limits exist

X monitors account activity for spam-like behavior. If you post, reply, or follow too quickly, X may:
- Temporarily restrict your account
- Flag your account for review
- Permanently suspend your account

OutreachGuy automatically enforces safe limits so you don't have to worry about this.

## Current limits

| Action | Limit | Resets after |
|--------|-------|--------------|
| **Replies** | 10 | 30 minutes |
| **Posts** | 1 | 4 hours |
| **Threads** | 1 | 4 hours |
| **Quote tweets** | 1 | 4 hours |
| **Retweets** | 1 | 1 hour |
| **Likes** | 20 | 1 hour |
| **Follows** | 20 | 1 hour |
| **Follows (daily)** | 100 | 24 hours |
| **Unfollows** | 20 | 1 hour |
| **DMs** | 10 | 1 hour |
| **DMs (6 hour)** | 50 | 6 hours |
| **DMs (daily)** | 100 | 24 hours |

## How it works

1. **Before each action**, OutreachGuy checks if you're within limits
2. **If within limits**, the action proceeds normally
3. **If at limit**, the AI pauses that action type and focuses on other tasks
4. **Limits reset automatically** after the time window passes

## What happens when you hit a limit?

The AI will:
- Stop attempting that action type
- Continue with other tasks that aren't limited
- Resume the limited action once the window resets

You don't lose any energy when an action is blocked by rate limits.

## Per-project limits

Rate limits are tracked per project (per X account). If you have multiple projects with different X accounts, each has its own separate limits.

## Tips for staying within limits

- **Spread out missions** — Don't schedule multiple reply-heavy missions at the same time
- **Use varied briefs** — Mix different action types (replies, posts, likes) in your strategy
- **Let the AI prioritize** — The AI will automatically work around limits

## FAQ

### Can I increase my rate limits?

No. These limits are set to protect your X account from restrictions. They're based on X's known thresholds and our experience with safe automation.

### Why is my mission not posting?

If you've already posted recently, you may have hit the 1 post per 4 hours limit. Wait for the limit to reset, or check if your mission can do other actions like replying instead.

### Do likes and follows share the same limit?

No. Each action type has its own separate limit. You can do 20 likes AND 20 follows in the same hour.

### What about reading actions?

Reading actions (searching tweets, viewing profiles, finding leads) have no rate limits. Only actions that create or modify content are limited.
