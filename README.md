Daytona Archive
=======
This is where we store our old repos. When projects are too inactive or too embarrassing to show to the public this is where you should sweep them under the carpet.


## To bundle

1. Clone the repo you want to archive  

2. Create a bundle with all branches
 ```bash
 git bundle create BUNDLE_NAME.bundle --all
 ```

3. Move the bundle file to this repo and push it up!

4. Delete the old repo

## To unbundle
To revive a repo, treat the bundle just like a remote, using fetch
```bash
git fetch BUNDLE_NAME.bundle refs/heads/\*:refs/remotes/bundle/\*
```
