# GitHub Event Data

This is a collection of sample payloads for the various events available via
GitHub WebHooks. This data was gathered for testing GitHub integrations.

*NOTE: The data is currently being gathered. Please be patient, or contact me
if you're interested in helping.*

## Events

GitHub supports the following events:

* `push` - Any git push to a Repository.
* `issues` - Any time an Issue is opened or closed.
* `issue_comment` - Any time an Issue is commented on.
* `commit_comment` - Any time a Commit is commented on.
* `pull_request` - Any time a Pull Request is opened, closed, or synchronized (updated due to a new push in the branch that the pull request is tracking).
* `pull_request_review_comment` - Any time a Commit is commented on while inside a Pull Request review (the Files Changed tab).
* `gollum` - Any time a Wiki page is updated.
* `watch` - Any time a User watches the Repository.
* `download` - Any time a Download is added to the Repository.
* `fork` - Any time a Repository is forked.
* `fork_apply` - Any time a patch is applied to the Repository from the Fork Queue.
* `member` - Any time a User is added as a collaborator to a non-Organization Repository.
* `public` - Any time a Repository changes from private to public.
* `team_add` - Any time a team is added or modified on a Repository.
* `status` - Any time a Repository has a status update from the API.

## GitHub Documentation

* [Repo Hooks API](http://developer.github.com/v3/repos/hooks/)
* [Event Types](http://developer.github.com/v3/activity/events/types/)
* [Post-Receive Hooks](https://help.github.com/articles/post-receive-hooks)

## License

All documentation and sample data is free for use, without restriction.
Attribution is not required.
