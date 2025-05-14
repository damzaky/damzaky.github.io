# How to Deploy a New Individual Repository to Playground
1. Make the repository
2. Go to Settings -> Actions -> General -> then check "Read and write permissions"
3. Add this file https://github.com/damzaky/online-pitch-music-note-and-loudness-meter/blob/main/.github/workflows/deploy.yml
4. Push to remote repository
5. If the deployment succeeds, go to Settings -> Pages -> Deploy from Branch -> `gh-pages`
6. Go to https://github.com/damzaky/damzaky.github.io -> Actions -> Manual run "Build and Deploy Jekyll Site"
