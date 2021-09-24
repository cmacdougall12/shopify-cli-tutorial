# NOTES

## Download starter theme onto local machine
- have store and theme
- use shopify cli reference to pull theme into local (https://shopify.dev/themes/tools/cli)
- can't use shopify cli with development store if you only have a partner account (need to be store owener or have a staff account)
- login to your store `shopify login --store [DOMAIN]`
- navigate to correct directory and `shopify theme pull` - this will download all theme files to local directory.

## Add Development theme to shopify store and connect to Github
- `shopify theme serve` - uploads theme as a development theme to the store you're connected to (localhost, store editor, previewlink are given) - "doesn't exists, but exists - need to connect to github"
- create git repo (git init, add, commit) - remote add etc. and then push to github.
- add theme on store admin page and connect to github
- now development theme will show up on store admin theme page

## Making changes and pulling and pushing changes
- When making changes locally and pushing too github
  - localhost link will show changes in realtime
  - when local changes are pushed, the development theme will automatically sync on store admin theme page 
- when making changes on the online editor use '`shopify theme pull` to bring changes to local environment
  - or else remote changes from editor will be lost on a push 
- 



