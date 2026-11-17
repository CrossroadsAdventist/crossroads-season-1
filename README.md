# Crossroads — Season 1 player (GitHub Pages)

A shareable web player for all 21 Season 1 episodes of Crossroads.
The page and the audio live together in this folder, so the player works
from any device or Google account — no Spotify needed.

## What's in this folder

- `index.html` — the player page (episode list, Play All, seek, back-to-back
  auto-advance, remembers where you stopped).
- `episode-01-…mp3` … `episode-21-…mp3` — the 21 finished episode masters
  (full quality, 192 kbps). Total ~613 MB; every file is under GitHub's
  100 MB per-file limit; the whole site is under the 1 GB Pages limit.
- `cover.jpg` — the show cover art (800 px).

## How to publish it (GitHub Pages)

1. Create a free account at https://github.com (if you don't have one).
2. Install GitHub Desktop (https://desktop.github.com) and sign in.
   (The episodes are 19–51 MB each, and GitHub's website uploader only
   takes files up to 25 MB — GitHub Desktop handles them fine.)
3. In GitHub Desktop: File → New Repository…
   - Name: `crossroads-season-1`
   - Local path: pick an empty folder on your computer
   - Leave it as a public repository, then Create Repository.
4. Copy everything from this folder into that repository folder.
5. In GitHub Desktop, write a commit message (e.g. "Season 1 player"),
   click Commit, then Publish repository (make sure it stays Public).
6. On github.com, open the repo → Settings → Pages → under "Branch"
   choose `main` and `/ (root)`, then Save. The site goes live within a
   few minutes at: `https://<your-username>.github.io/crossroads-season-1/`

## Updating it later

Season 2 gets its own repository (`crossroads-season-2`) the same way —
a single repo would grow past GitHub Pages' 1 GB site limit. To add an
episode to this Season 1 site, drop the new MP3 into the repo folder,
add its entry to the EPISODES list in `index.html`, commit and push.

## Other places to listen

- Spotify: https://open.spotify.com/show/4kSRaNLoz4u34nFCMUw7KV
- Google Drive folder (full-quality files + the Episodes 1–21 play-all
  recording): https://drive.google.com/drive/folders/1ycbZTgMK3zHMKOeKOfqJWGrsqoL8gJnZ
