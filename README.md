# Cloud Island Delivery Team

## Cloudflare Pages

1. Create a Pages project and choose **Import an existing Git repository**.
2. Select `redfisharthur-beep/Cloud-Island-Delivery-Team` and use the `main` branch.
3. Choose **None** as the framework preset.
4. Set the build command to `exit 0` and the build output directory to `.`.
5. Deploy. The site serves the root `index.html`.

The game is an HTML5 canvas project with optimized WebP art assets and no package installation or build step. It is designed for landscape mobile play. Tapping the play icon requests fullscreen and landscape orientation where supported. For an app-like fullscreen launch, install it to the home screen; the web app manifest requests fullscreen landscape mode. Touch controls use a circular joystick and icon-only combat buttons on phones. Desktop uses A/D to move, W to jump, S to crouch, P to dash, O to use an attack charge, and L to spend a healing charge. A life bar and an icon-only inventory/status strip stay visible during play. Each of the three stages ends with a boss; attack charges can damage it, or players can activate the three floor sigils in order. Later bosses add slow and poison effects. Pickups include wing, shield, star, attack charges, and healing charges; rare pickups rise in a tall light beam. Collectible coins use a beveled, rotating gold design with stage-specific metal accents. Stage-specific carved platforms, moving lifts, wind currents, frame-by-frame courier animations, and smoothly telegraphed enemy lunges round out the routes.
