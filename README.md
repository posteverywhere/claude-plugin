# PostEverywhere for Claude

Write, schedule and publish social media posts from a conversation with Claude. PostEverywhere posts to Instagram, TikTok, YouTube, LinkedIn, Facebook, X, Threads, Pinterest, Bluesky, Telegram, Discord and WordPress from one place, and shows you how your posts performed.

## What you can ask Claude

- "Post this announcement to LinkedIn and X tomorrow at 9am."
- "Turn this blog post into a week of posts for Instagram, Threads and Bluesky."
- "What did I post last week, and which post did best?"
- "Why didn't my TikTok post go out? Fix it."
- "Connect my YouTube channel."

## What's included

**The PostEverywhere connector** (`https://mcp.posteverywhere.ai/claude`) gives Claude tools to list your accounts, create and schedule posts, upload media from a link, manage campaigns, read analytics and retry failed posts. You sign in to your PostEverywhere account the first time you use it.

**Skills** that teach Claude how to use those tools well:

| Skill | What it does |
|---|---|
| `schedule-social-posts` | Writes a post for each platform's rules, shows you a draft, and schedules or publishes it after you confirm |
| `plan-content-calendar` | Plans a week or month of posts around a goal and creates them as drafts for review |
| `review-post-performance` | Summarises how your posts performed and suggests what to try next |
| `fix-failed-posts` | Finds posts that failed, explains why, fixes the cause and retries |
| `connect-social-accounts` | Connects a new social account or reconnects one that stopped working |

Claude always shows you a post before it goes live. Nothing is published to your accounts unless you ask for it.

## Requirements

- A PostEverywhere account with a plan or an active free trial. Start at [posteverywhere.ai](https://posteverywhere.ai).
- The social accounts you want to post to, connected in PostEverywhere. Claude can give you a link to connect them.

## Data and privacy

The plugin contains only instructions (skills) and the address of the PostEverywhere connector. It runs no code on your computer.

When you use it, Claude sends the text, links and media you ask to post, and your requests to list or change posts, to PostEverywhere at `mcp.posteverywhere.ai`, over HTTPS, signed in as you. PostEverywhere publishes to the social platforms you choose, only when you ask. Read the [privacy policy](https://posteverywhere.ai/privacy) and [terms](https://posteverywhere.ai/terms).

## Support

Email support@posteverywhere.ai, or read the documentation at [posteverywhere.ai/docs](https://posteverywhere.ai/docs).

## License

MIT. See [LICENSE](LICENSE).
