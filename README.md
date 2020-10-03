# Interesting Things

A collection of things that make me go "🤔"
Currently quite disorganized, pay no attention to the order or selection of things atm

## Vercel
https://github.com/vercel/release - This project generates GitHub releases and populates it with commits since the last release. Looks like quite a useful tool. You can install it globally to the CLI and publish new releases with `release major`, `release minor`, `release patch`, and `release pre`.

https://github.com/vercel/hazel - super light update server for deployed electron apps in the wild. It will register updates automatically from releases on a GitHub repo.

https://github.com/vercel/micro - tiny HTTP client. I thiiiiink it might be used by default in all Vercel functions.

## Next
https://github.com/cyrilwanner/next-optimized-images - Community plugin for Next.js that does optimized image loading. At time of writing, version 3 is in development which brings a bunch of useful changes and improvements.

## Javascript
https://github.com/jaredpalmer/razzle - low-config react SSR setup. Also check docs at https://razzlejs.org/

https://blitzjs.com/docs/getting-started - Fullstack Javascript with Next.js + ORM, inspired by Ruby on Rails

https://swr.vercel.app/getting-started - data-fetching library within React, using hooks.

## Components
https://draftjs.org/?ref=producthunt - Rich text editor in React

## Laravel
https://tenancy.dev/docs/tenancy/1.x/tenant-setup - library / group of libraries that makes handling complex, real-world multi-tenancy scenarios in Laravel easier.

https://github.com/baopham/laravel-dynamodb - use AWS DynamoDB with Laravel applications.
 - https://www.dynamodbguide.com/the-dynamo-paper/ also see this guide
 - https://www.dynamodbbook.com/ and this book
 
https://github.com/mpociot/versionable - make models versionable and keep a history of changes within them.
 
https://laravelpackage.com/09-routing.html - building PHP packages for Laravel
https://github.com/Jeroen-G/laravel-packager - a CLI to template Laravel Packages

https://github.com/laravel-frontend-presets/tall - the TALL preset, great setup for new projects.

https://beyondco.de/docs/laravel-websockets/getting-started/introduction - Use websockets with laravel
 
## Flutter
- https://flutterawesome.com/easy-to-use-podcast-player-app-written-in-flutter-and-dart/
- https://flutterawesome.com/a-git-services-including-github-built-with-flutter/
- https://flutterawesome.com/a-beautiful-task-planner-app-design-made-in-flutter/
- https://flutterawesome.com/twitter-clone-using-flutter-framework/
- https://flutterawesome.com/e-commerce-app-built-in-flutter/
- https://flutterawesome.com/smart-course-app-built-in-flutter/
A sample of example flutter applications

## React Native
https://github.com/vadimdemedes/tailwind-rn

## SwiftUI
https://fuckingswiftui.com/ - great resource for learning SwiftUI

## Api / Project
https://thispersondoesnotexist.com/ - This could be useful to power an API that generates avatars for email addresses when building / testing user interfaces in apps. I'm thinking that a call could be made to an API with a name / email and the API would hash it, check a DB to see if a profile has been created for it, and then if it doesn't exist it would create the image using this website OR if it does exist it would return a link to the cached image. If the image is still being created, it could use Vercel or Netlify with automatic deploys to serve the images?

https://skeletonreact.com/?ref=producthunt - cool for creating 'loading state' SVG animations for apps.

## Demo
https://github.com/jaredpalmer/minimum-viable-saas - incredibly compact SaaS demo with stripe and firebase.

## Services
https://formium.io/ - looks like a VERY interesting hosted form solution. Also website design looks nice.

https://lottiefiles.com/getting-started - community / inspiration site built around Lottie and Adobe After Effects.

## Hosting
https://www.gigalixir.com/ - hosted elixir

## MacOS apps
https://github.com/turkenh/KubeContext - manage Kubernetes contexts

## Blog
- https://jenssegers.com/
- https://andrew.wang-hoyer.com/experiments/fractals/

## Posts
- https://hugozap.com/posts/how-to-finish-your-side-project/
