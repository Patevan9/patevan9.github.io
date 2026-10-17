# patevan9.github.io

The root GitHub Pages site for this account. It exists to serve
`app-ads.txt` at the root of the domain, where Google AdMob looks for it:

https://patevan9.github.io/app-ads.txt

It authorises Google (AdMob) to sell ads in Patrick Lippy's apps, starting
with Rollabop. Keep it here and unchanged unless AdMob gives a new line.

The project websites are separate repositories and are not affected:

- Rollabop: https://patevan9.github.io/rollabop-website/ (repo `rollabop-website`)
- Lippy Robotics Labs: https://patevan9.github.io/lippyrobotics.github.io/

`.nojekyll` tells GitHub Pages to publish the files exactly as they are.

## Lippy Robotics Labs homepage

`index.html` and `assets/` are the Lippy Robotics Labs homepage, served at
https://patevan9.github.io/. Its source and notes live in
`Patevan9/scout-ai-research` → `lippy-labs-website/`.

**Rollback:** the branch `backup-before-labs-site` keeps the site exactly as it was before
the homepage was added. To undo, revert the homepage commit
(`git revert <commit>`) — that removes only `index.html` and `assets/` and leaves
`app-ads.txt` untouched.
