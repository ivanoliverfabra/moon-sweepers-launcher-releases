# Moon Sweepers Launcher

A Windows launcher for [Moon Sweepers](https://store.steampowered.com/app/5335510): keep a list of servers, see who's online, install and update the game, and join with one click.

This repository only hosts **release builds** of the launcher. The source code is not public.

## Download

Get the latest version from the [Releases page](../../releases/latest) and run it.

- **Windows 10 or newer** (64-bit). Other platforms aren't supported.
- Windows may show a SmartScreen warning the first time you run it, because the launcher isn't code-signed yet. Choose **More info → Run anyway** if you downloaded it from this page.

## Features

- **Server list:** save servers, see their status and player count, search and sort.
- **One-click play:** joins the server you selected. Server passwords are stored encrypted on your PC and never shown again.
- **Game install and updates:** downloads, verifies and installs the game for you, and repairs it if files go missing.
- **Self-updating:** the launcher checks for new versions in the background and offers a restart when one is ready.
- **Links:** `moonsweepers://` links open the launcher and offer to add the server.

## Signing in

The game download is only available to approved players. On first launch you sign in with Discord. If your account isn't approved yet, ask the server owner to add you.

## Updates

You don't need to come back here after the first install. When a new version is downloaded, a **Restart** button appears in the launcher's sidebar. The launcher won't restart while the game is running or while the game is installing.

## Troubleshooting

| Problem | Try this |
| --- | --- |
| The game says it's damaged or won't start | Open the **Game** page and choose **Repair**. |
| An install fails or stops | Choose **Try again**. Downloads resume where they stopped. |
| Can't sign in | Make sure you're on the approved list, then sign in again. |
| The launcher won't update | Check your internet connection, then restart the launcher. You can also download the newest version from Releases and run it over the old one. |
| The old icon still shows after an update | Windows caches icons. Restart Explorer or your PC. |

## Reporting problems

Open an [issue](../../issues) and include:

- the launcher version (shown in the Releases tag you installed),
- what you did and what happened,
- any message the launcher showed.

Please never post your server passwords or session information.

## Disclaimer

This is an unofficial community launcher. It is not affiliated with or endorsed by the developers of Moon Sweepers.
