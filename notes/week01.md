##Snags and fixes
- First push failed, had to fix git defaulting to master instead of main for the new repo
- Magenta wasn't reachable by name, had to set up Avahi in the nixos config to get it to show up using .local for ssh
- Didn't have /var/lib/libvert/images, had to create the folder so that i could download the alpine ISO into it
- Alpine VM had no IP address, Alpine defaulted to have networking switched off so i needed to get it switched on and running

## Things I learned
- How the underlying Git infra works
- How to set up and use a new Git repo
- How to set up and run a new VM on my test server
