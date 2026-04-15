# WoVR Project Page

Single-page academic website for:

`WoVR: World Models as Reliable Simulators for Post-Training VLA Policies with RL`

## Local preview

From this directory:

```powershell
python -m http.server 8000
```

Then open `http://127.0.0.1:8000`.

## Deployment notes

The intended final destination is the GitHub Pages organization site:

`https://wovr.github.io/`

GitHub CLI can create and push the repository, but standard GitHub accounts cannot create a new
organization directly through the public CLI/API flow. If the `wovr` organization does not exist yet,
create it once in the GitHub web UI, then from this directory run:

```powershell
gh repo create wovr/wovr.github.io --public --source . --remote origin --push
```

If you first publish under a personal namespace and later move it into the organization, transfer the
repository to `wovr` and keep the repository name as `wovr.github.io`.
