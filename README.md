# My dotfiles
This repo contains the dotfiles for my system.

Managed using [GNU Stow](https://www.gnu.org/software/stow/).

## Dependencies
- stow
- git

## Setup
- Install dependencies.
- Clone the repo.

```
cd ~
git clone https://github.com/nahilrasheed/dotfiles.git
cd dotfiles
```
- Use stow to set symlinks for each program.
```
stow program1 program2
```
- To create symlink, setup the dotfiles following stow [conventions](https://www.gnu.org/software/stow/manual/stow.html#Terminology).

---