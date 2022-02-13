# Astro NetlifyCMS Blog Template Starter

This repo contains the base code needed to deploy a standalone blog built on Astro, NetlifyCMS, and backed by Github.

## Deployment / New Site Guide
Follow these steps in order to use this repo to start a new blog site:

- Clone this repo locally and create a new origin to the new repo for the new site:
`git clone git@github.com:srobertson421/astro-cms.git`
`cd astro-cms`
`git add origin new-site <new-site-repo-url>`
`git push origin new-site`

- From the Netlify dashboard, create a new site from the new github repo.

- In the Netlify settings for the new site go to the "Identity" section and enable Identity. Be sure to make the identity invite-only and to enable Git-Gateway.

- Now you are free to make changes to the site via your local clone and push those up to the new site repo. Alter the styles, layouts, and even the available collections for the CMS to use via the `config.yml` in the `/public/admin` folder.

- Next you may add a custom domain via Netlify as well as any other settings that are necessary.

- Finally you need to invite the necessary users via Netlify Identity. This will send them an invite email which will contain a link to the deployed CMS and allow them to finalize the login by creating a password.