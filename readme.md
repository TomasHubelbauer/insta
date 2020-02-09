# Instagram

Scrapes followers and posts off Instagram and emails changes.

## Running

`node . ${handles}`

`handles` is a comma-separated string of Instagram handles.

A file name `${handle}.data.json` will be created.

If `../self-email` is present on the system, a notification email will be sent
with follower/following/posts changes.
