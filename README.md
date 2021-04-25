# Battle Nations
This repository contains the client side assets for the Battle Nations Rewritten project. For precompiled releases, please visit the `Access` tab on our [website](https://battlenations.net/).  

If you'd like to help develop the game in either coding or non-coding capacities, please join the Battle Nations [Discord](https://discord.com/invite/77yCMqM) and get in touch!


# Development Information
Below is information relevant to developers working on the project.  
**Developers Please Read This Section Before Doing Any Development Work!**

## Unity
We are currently using Unity 2019.4.17f1 for this project but will be upgrading to a 2020.2.X LTS release.

## Branch Layout
The repo is organized into 3 main branches: 
- **release**: Code from the latest general public release of the game.
- **dev-stable**: Code that has proven stable enough during development to allow for beta testing by the general public.
- **dev-unstable**: Code that is still under heavy development and isn't ready for beta testing yet.

When working in this repo, please create a new branch with a descriptive name about the work you will be working on in that branch. When working on features, please prefix branch names with `feature/` and when working on bug fixes, please prefix with `bug/`. When you are ready to merge your work, please create a pull request to merge changes into dev-unstable. When dev-unstable reaches a point of stability, please create a pull request to merge the changes into dev-stable so beta testing on it can be done.

## Commit Messages
Please be descriptive in commit messages so other devs can more easily know what changes have been made and for easier changelog generation.

## CI/CD
In the future, Github Actions will be setup to do automated unit testing and project builds.
