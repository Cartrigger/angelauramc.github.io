# Workflows

`build.yml` - Simply uploads a build artifact of the static website\
`deploy.yml` - Builds, uploads, and deploys the uploaded artifact to github pages

# Issues

You may encounter that the deploy workflow does not work, this is because github pages prefixes a subdirectory with your repository name when deploying. This breaks the static site generated by Vuepress

Use cloudflare pages instead or test locally with `npm run start`

### If that is not possible

`deploy(legacy).yml` - Builds and pushes the static site to the branch `gh-pages`. This stops the automatic subdirectory addition from happening

This may break other pages that you have deployed and should be avoided if possible. Please use _cloudflare pages_ instead

If that is not possible, you may edit the `base` property in `config.js` and use `deploy.yml`, this may break asset retrieval (images in our case)
##### Remember to revert this change on the PR branch
