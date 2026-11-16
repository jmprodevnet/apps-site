# apps.jmprodev.net
Public information pages for applications run by jmprodev.net, served by GitHub Pages at <https://apps.jmprodev.net>.

## Pages
- `personal-assistant/`: home page of the Personal Assistant app.
- `personal-assistant/privacy/`: its privacy policy. Google requires both addresses before it publishes the app's sign-in for Gmail.

## How it is served
- GitHub Pages builds from the `main` branch, root folder.
- `CNAME` holds the custom domain; GitHub Pages reads it.
- At the DNS host (GoDaddy), a `CNAME` record points `apps` at `jmprodevnet.github.io`.

Plain HTML and one stylesheet, with no build step, so a change is an edit to a file.

## Keep the privacy policy true
The privacy policy is a public statement about what the app does with mail. When the app changes what it reads, keeps, or for how long, change the policy in the same week and update its "Last updated" date.
