# Cloud Island Delivery Team

## Cloudflare Pages

1. Create a Pages project and choose **Import an existing Git repository**.
2. Select `redfisharthur-beep/Cloud-Island-Delivery-Team` and use the `main` branch.
3. Choose **None** as the framework preset.
4. Set the build command to `exit 0` and the build output directory to `.`.
5. Deploy. The site serves the root `index.html`.

The game is an HTML5 canvas project with two optimized WebP art assets and no package installation or build step. It is designed for landscape mobile play. Tapping the play icon requests fullscreen and landscape orientation where supported. For an app-like fullscreen launch, install it to the home screen; the web app manifest requests fullscreen landscape mode. Touch controls use icons only; keyboard controls are also supported on desktop. Moving platforms and visible wind currents add timing-based routes.
