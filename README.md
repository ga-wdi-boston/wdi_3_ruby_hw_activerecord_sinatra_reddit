# Sinatra/ActiveRecord Homework: Reddit Clone

[Reddit](http://www.reddit.com/) is awesome, and this weekend you're going to clone it. 

Subreddits are topic-driven containers for submissions. For example, you may have a Subreddit on ruby programming, where people would be encouraged to make submissions about Ruby programming. Anyone can create new subreddits. Each subreddit should have a front index page which displays submissions in order of votes, and also a 'newest' page that shows the newest ones first.

Submissions (stories) are either links or text (not both, very similar to hacker news). Submissions can be created anonymously by anyone. Submissions can be upvoted or downvoted by anyone. 

All submissions have a comment page where anyone can leave anonymous comments. 

You should also have a 'front' page, which shows an aggregate of all submissions and acts like its own meta subreddit.

## Suggested URL structure examples

- `/` Shows the most popular submissions from all subreddits
- `/new` Shows form for creating a new subreddit
- `/newest` Shows newest submissions from all subreddits
- `/r/sub-reddit-name` Shows the most popular submissions from a specific subreddit
- `/r/sub-reddit-name/new` Shows form for creating new submission
- `/r/sub-reddit-name/newest` Shows newest submissions for this subreddit
- `/r/sub-reddit-name/submission-name` Shows a specific submission's comment page in a specific subreddit. Maybe you can add new comments from a form here?

### Bonuses

- Style it to look like Reddit
- Use strings for the urls instead of id numbers. 
- Figure out how to nest comments on each other, so that users can respond to each other in conversation
- Write a system for displaying submissions on a subreddit that is a combination of submission age and total upvotes. Even if something is highly upvoted, it should eventually slide down the front page. If you do this bonus, also create an 'top' page for the subreddits, which top submissions of all time for that subreddit.
