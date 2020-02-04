## Publish a new major version ##
0. `npm login` #Log in your https://www.npmjs.com/ account
1. `git add -A`
2. `git commit -m "Some updates'`
3. `git push origin master`
4. `lerna version major`
5. `lerna publish from-git`

[Resource](https://blog.npmjs.org/post/186494959890/monorepos-and-npm)

## Resources about private package hosting ##
[About Private packages](https://docs.npmjs.com/about-private-packages)
[Private package collaborators](https://docs.npmjs.com/adding-collaborators-to-private-packages-owned-by-a-user-account)
[Private package collaborator teams](https://docs.npmjs.com/managing-team-access-to-org-packages)