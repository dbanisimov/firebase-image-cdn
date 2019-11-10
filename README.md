# Firebase Image CDN 🔥🖼
Implementation of a simple Image CDN using Firebase Hosting, Functions, and Storage

## Demo
[Firebase Image CDN](https://fir-image-cdn.web.app/), featuring Kusya the cat 😺

## Quickstart
You must have a Firebase account, `firebase-tools` installed and logged in. Refer to Firebase [documentation](https://firebase.google.com/docs/web/setup) for more details.

1. `npm install`
2. `firebase init`
3. `cd ./functions && npm run build && cd -`
4. `firebase serve`

Upload images to your Firebase Storage using Console and use the image name (or full key in the bucket) as the source image name for the CDN.

## Deploy
`firebase deploy`

Please note Firebase Storage rules in this project allow public read of all files in the bucket.