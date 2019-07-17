# RedditBanSyncer
Syncs bans between all subreddits the bot moderates when bans include a given tag.

## Usage
See the /r/RequestABot sticky for setting up a reddit bot.

https://www.reddit.com/r/RequestABot/comments/3d3iss/a_comprehensive_guide_to_running_your_bot_that/

Fill in the empty strings in the bansync.py (the login fields). Alter the global ban tag as required.

Once the bot is running, add it as a mod to any subreddit with ban permissions and it will monitor the mod logs for the tag and ban the given user in all other subreddits it moderates.
