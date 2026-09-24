# EeveeSpoti

**Combined EeveeSpotifyReincarnated + spoti.pw (official Liquid Glass build)**

This version builds spoti.pw the **proper** way (their official `make release` process) so you actually get real Liquid Glass on iOS 26/27, then injects EeveeSpotify on top for full premium.

## Recommended

- Spotify **9.1.78** decrypted IPA (required for current spoti.pw)
- iOS 26 or 27 for Liquid Glass

## How to build

1. Get a decrypted Spotify **9.1.78** IPA
2. Go to **Actions** → **Build Combined Eevee + spoti.pw IPA**
3. Paste the direct link to the IPA
4. Run the workflow
5. Download the artifact
6. Sign & install

After install:
- Open Mod Settings → make sure **Redesigned UI** is ON
- Force close Spotify and reopen
- Turn **Spoof Premium OFF** in spoti.pw (let Eevee handle it)

## Credits

- [skopevoj/spoti.pw](https://github.com/skopevoj/spoti.pw) (official build process)
- [SideloadLabs/EeveeSpotifyReincarnated](https://github.com/SideloadLabs/EeveeSpotifyReincarnated)
