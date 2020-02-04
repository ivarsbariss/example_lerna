## Publish a new major version ##
1. `npm login` #Log in your https://www.npmjs.com/ account
2. `git add -A`
3. `git commit -m "Some updates'`
4. `git push origin master`
5. `lerna version major`
6. `lerna publish from-git`

[Resource](https://blog.npmjs.org/post/186494959890/monorepos-and-npm)

## Resources about private package hosting ##
[About Private packages](https://docs.npmjs.com/about-private-packages)<br />
[Private package collaborators](https://docs.npmjs.com/adding-collaborators-to-private-packages-owned-by-a-user-account)<br />
[Private package collaborator teams](https://docs.npmjs.com/managing-team-access-to-org-packages)<br />