# Create or Update PR Comment API Demo

Oftentimes, it's nice to have a bot user post some information to a Pull Request.
For example, imagine a link to a pre-production preview link for the branch,
or infrastructure-as-code diffs.

However, GitHub doesn't provide a simple way to "create or update" a comment for
a particular bot message. So, I built a simple serverless solution to work around
this using the GitHub API.

## Demo

To see this solution in action, check out
[the Demo Pull Request](https://github.com/blimmer/github-pr-comment-api-demo/pull/1).

As you'll see, the first time the API is called, a new comment is created. Then,
when the API is subsequently called, the existing comment will be updated.

By updating an existing comment, bot-based noise is significantly reduced, while
the history of each bot post is retained in the "edited" dropdown.

<img width="668" alt="Screen_Shot_2021-12-20_at_9_50_55_PM" src="https://user-images.githubusercontent.com/630449/146873107-c8e3ea7a-c395-4e1b-b5c3-5564e765fb77.png">

## Let's Connect!

I'm a freelance architect and engineer who loves focusing on Developer Experience
and tooling. Learn more at [benlimmer.com/freelance](https://benlimmer.com/freelance?utm_source=github&utm_campaign=create-or-update-pr-comment-demo).
