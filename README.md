# THIS DOES NOT WORK

Unfortunately there's no `.git` repository during or after compilation.

Heroku have said they're looking into to providing this kind of information in
the future, but without any indication of when we can expect to see something.

> You can't get the git sha during the build. Not by querying the API either,
> because the release that's being created has not been created yet (and so
> won't show up in the list of releases).

> We're working on making metadata like this available during build and at
> runtime. Stay tuned.

https://discussion.heroku.com/t/can-a-custom-buildpack-put-the-current-git-commit-sha-into-apps-env/932
