# GitHub profile README setup

1. Open https://github.com/anshadpp/anshadpp (the public profile repository).
2. Upload `README.md` at the repository root. Replace the old README only after reviewing it.
3. Create an `assets` directory and upload `terminal-hero.svg` and `terminal-footer.svg` into it. Preserve these exact paths.
4. Commit changes and visit https://github.com/anshadpp to check your profile.
5. If the typing animation or stats widgets do not load, they depend on external services; the rest of the profile will still work. You may remove those `<img>` tags if preferred.
6. GitHub README files cannot run custom JavaScript, so the terminal is decorative and the SVG effects are subtle, not interactive mouse tracking. Animation support can vary by viewer and reduced-motion preferences.
7. Before publishing, verify the experience bullets and project links against your own records. Do not upload private company code or credentials.

Optional local Git workflow (from a cloned `anshadpp` profile repository):

```bash
git add README.md assets/terminal-hero.svg assets/terminal-footer.svg
git commit -m "Refresh profile README with terminal theme"
git push
```
