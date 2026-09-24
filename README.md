# EeveeSpoti

**Combined EeveeSpotifyReincarnated + spoti.pw**

One clean IPA with:
- Full premium spoof from **EeveeSpotifyReincarnated**
- Liquid Glass redesign, word-by-word lyrics, audio effects, Live Activity from **spoti.pw**

No conflicts. spoti.pw Spoof Premium is left off so Eevee handles premium properly.

## Recommended Spotify version

- **9.1.78** (best compatibility with current spoti.pw v0.22.0)
- Eevee supports up to ~9.1.84

## How to build

1. Get a **decrypted** Spotify IPA (use decrypt.day, BagBak, etc.)
2. Go to the **Actions** tab of this repo
3. Select **Build Combined Eevee + spoti.pw IPA**
4. Click **Run workflow**
5. Paste the direct download link to your decrypted IPA
6. Wait for the job to finish
7. Download the artifact (`EeveeSpoti-*.ipa`)
8. Sign it with SideStore / Feather / AltStore / your certificate

## Notes

- The workflow automatically fetches the latest EeveeSpotifyReincarnated and latest spoti.pw debs
- Injection is done with cyan
- After installing, open Spotify → go into Mod Settings (spoti.pw) and make sure **Spoof Premium is OFF**
- Then open Eevee settings and do a Reset Data if needed

## Credits

- [SideloadLabs/EeveeSpotifyReincarnated](https://github.com/SideloadLabs/EeveeSpotifyReincarnated)
- [skopevoj/spoti.pw](https://github.com/skopevoj/spoti.pw)
- cyan by asdfzxcvbn

Not affiliated with Spotify.
