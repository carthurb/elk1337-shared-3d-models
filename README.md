# elk1337 shared 3D models

Free printable files shared on [elk1337.com/downloads](https://elk1337.com/downloads/).

Downloads are served from this repo's [latest release](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest). Every release uses the same file names, so each link below always gets the newest version.

| Model | File | Direct download |
|---|---|---|
| 1:10 scale CCW-style jester driver | `jester-driver-1-10-scale-ccw.stl` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/jester-driver-1-10-scale-ccw.stl) |
| 1:10 scale CCW-style jester driver, torso only | `jester-driver-1-10-scale-ccw-torso-only.stl` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/jester-driver-1-10-scale-ccw-torso-only.stl) |
| Jester driver paint guide (PDF) | `jester-driver-1-10-scale-ccw-paint.pdf` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/jester-driver-1-10-scale-ccw-paint.pdf) |
| Dovetail comp bed for CCW J&H | `dovetail-comp-bed-ccw-jh.stl` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/dovetail-comp-bed-ccw-jh.stl) |
| CCW J&H forward electronics tray | `electronics-tray-ccw-jh-forward.stl` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/electronics-tray-ccw-jh-forward.stl) |
| Anvil sliders (CCW Jekyll & Hyde, Anvil cab-only body) | `anvil-sliders.stl` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/anvil-sliders.stl) |
| '57 Del Rio comp cut cab | `del-rio-cab-comp-cut.stl` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/del-rio-cab-comp-cut.stl) |
| '57 Del Rio comp cut cab backplate | `del-rio-backplate-comp-cut.stl` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/del-rio-backplate-comp-cut.stl) |
| '57 Del Rio uncut cab | `del-rio-cab-uncut.stl` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/del-rio-cab-uncut.stl) |
| '57 Del Rio uncut cab backplate | `del-rio-backplate-uncut.stl` | [download](https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/del-rio-backplate-uncut.stl) |

The comp cut Del Rio cab needs 5× M3 heat-set threaded inserts; the uncut cab needs 4×.

Link format: `https://github.com/carthurb/elk1337-shared-3d-models/releases/latest/download/<file name>`

## Publishing an update

1. Replace the file in [`downloads/`](downloads) under the same name and push.
2. Create a new release that includes every file, with the names unchanged. Files left out of the newest release stop downloading from the `latest` links.

```
gh release create <date> downloads/* --title "elk1337 downloads <date>" --latest
```
