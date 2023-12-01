# dotfiles

## Inspirations
- https://github.com/twpayne/dotfiles/tree/master/home
- https://github.com/onedr0p/dotfiles

## Install

Dependencies
* `brew`
* `chezmoi`
* `git`

Configure
* SSH key

Run:
```bash
chezmoi init hrpatel --ssh --verbose
chezmoi diff
chezmoi apply --dry-run --verbose (OPTIONAL)
chezmoi apply --verbose
```
