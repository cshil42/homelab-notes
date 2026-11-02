# homelab-notes

I set up this repo to record my progress toward the CompTIA Network+ and Red Hat RHCSA certifications. It holds lab configs, study notes, and write-ups of the projects I build along the way.

## Lab infrastructure

The lab laptop (`Magenta`) runs NixOS and hosts the lab VMs with KVM/libvirt. Its configuration is declarative: the flake and modules, shared across my machines, live in [cshil42/Nixos-configs](https://github.com/cshil42/Nixos-configs). The VM host setup is in [`config/Magenta.nix`](https://github.com/cshil42/Nixos-configs/blob/main/config/Magenta.nix).
