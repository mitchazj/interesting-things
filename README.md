# Interesting Things

A collection of things that make me go 🤔 Currently quite disorganized, pay no attention to the order or selection of things atm

## Vercel
https://github.com/vercel/release - This project generates GitHub releases and populates it with commits since the last release. Looks like quite a useful tool. You can install it globally to the CLI and publish new releases with `release major`, `release minor`, `release patch`, and `release pre`.

https://github.com/vercel/hazel - super light update server for deployed electron apps in the wild. It will register updates automatically from releases on a GitHub repo.

https://github.com/vercel/micro - tiny HTTP client. I thiiiiink it might be used by default in all Vercel functions.

## Next

https://github.com/cyrilwanner/next-optimized-images - Community plugin for Next.js that does optimized image loading. At time of writing, version 3 is in development which brings a bunch of useful changes and improvements.

## Api / Service
https://thispersondoesnotexist.com/ - This could be useful to power an API that generates avatars for email addresses when building / testing user interfaces in apps. I'm thinking that a call could be made to an API with a name / email and the API would hash it, check a DB to see if a profile has been created for it, and then if it doesn't exist it would create the image using this website OR if it does exist it would return a link to the cached image. If the image is still being created, it could use Vercel or Netlify with automatic deploys to serve the images?
