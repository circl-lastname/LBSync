# LBSync
Ladybird syncing script, allows the user to easily cherry-pick PRs from the Ladybird repository to the SerenityOS repository.

## Assumptions
* The Ladybird master branch exists in the repo
* `gh` is set up with your account and the LadybirdBrowser/ladybird repository as default
* `serenity_master` is the SerenityOS master
* `serenity_fork` is your SerenityOS fork's Git remote

## Usage
`lbsync` must be ran with the current directory being your Ladybird/SerenityOS Git repository, and with the IDs of the PRs you wish to sync.

Example:
```
../lbsync 123
```
```
../lbsync 123 456
```
