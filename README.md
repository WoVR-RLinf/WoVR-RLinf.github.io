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

`https://wovr-rlinf.github.io/`

For an organization page, the repository name must match the organization login exactly. Since the
organization login is `WoVR-RLinf`, the correct repository is `WoVR-RLinf.github.io`.

```powershell
gh repo create WoVR-RLinf/WoVR-RLinf.github.io --public --source . --remote origin --push
```

After pushing, enable GitHub Pages from the `main` branch root if it is not already enabled.
