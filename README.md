# case-sensitive-games.github.io

Public deploy target for Case-Sensitive Games — the live site at
<https://case-sensitive-games.github.io/>.

**Don't edit game files here by hand.** Each game lives in a private source repo
whose CI deploys its built page into a subdirectory of this repo on every push to
`main` (over a per-repo deploy key). Hand edits to those directories will be
overwritten by the next deploy.

| Path | Game | Source repo (private) |
| --- | --- | --- |
| [`/rogue-peaks/`](https://case-sensitive-games.github.io/rogue-peaks/) | Rogue Peaks | `Case-Sensitive-Games/rogue-peaks` |

The landing page (`index.html` at the root) is maintained directly in this repo —
add a card here when a new game starts deploying.

The site is intentionally unlisted: every page carries
`<meta name="robots" content="noindex">` so search engines won't list it — it's
reachable only by direct link. Keep the tag on any new page (and don't add a
`robots.txt` disallow, which would hide the tag from crawlers and defeat it).
