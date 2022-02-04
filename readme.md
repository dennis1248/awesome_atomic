# Awesome Immutable [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> image-based Linux desktops

This guide is for people looking for information on running image-based Linux distributions and associated tools and goodies. Note that these systems aren't totally immutable, but no one would ever click on an `awesome-anti-hysteresis` list. For this list server distributions like CoreOS and Flatcar are not included, this is intended for users who have been using traditional linux distributions on their desktop and need consolidated information. 

## Blogs

These should be enough to get you started.

- [“Immutable” → reprovisionable, anti-hysteresis](https://blog.verbum.org/2020/08/22/immutable-%E2%86%92-reprovisionable-anti-hysteresis/)- Colin Walters
- [The Birth of the Kubic Desktop](https://rootco.de/2017-11-16-hackweek-2017-conclusion/) - Richard Brown
- [Project Atomic + Docker: A post package world?](https://blog.verbum.org/2014/07/10/project-atomic-docker-a-post-package-world/) - Colin Walters - it's an older post but it checks out
- [Introducing flox - Nix for simplicity and scale](https://discourse.nixos.org/t/introducing-flox-nix-for-simplicity-and-scale/11275)- Barry Plunkett

## Talks and Videos

- [Kubic - openSUSEs Container Starship](https://speakerdeck.com/sysrich/kubic-opensuses-container-starship) - Richard Brown
- [openSUSE MicroOS](https://www.youtube.com/watch?v=nIwqzGbX-oc) - Richard Brown
- [Can MicroOS Desktop be your Daily Driver?](https://www.youtube.com/watch?v=6F7iCntjWB8) - Dario Faggioli
- [MicroOS Desktop: The Road to Daily Driving](https://www.youtube.com/watch?v=cZLckDUDYjw) - Richard Brown
- [19 talks on Fedora Silverblue and related technologies](https://silverblue.fedoraproject.org/elsewhere) - many recorded talks here, too many to list here, but worth it! 
- [ostree CLI for OS management](https://www.youtube.com/watch?v=B0xvrXkEwr4) - Denis Pynkin
- [Let's try Fedora Silverblue](https://www.youtube.com/watch?v=-hpV5l-gJnQ) - Adam Šamalik
- [How Nix and NixOS Get So Close to Perfect](https://christine.website/talks/nixos-pain-2021-11-10) - Xe
- [Fedora Silverblue: is this the FUTURE of Linux? - Project of the Month](https://www.youtube.com/watch?v=5TjIzUJtF-I) - older video but an excellent review of the major components
- [Learning the difference between Red Hat distributions and what Fedora Silverblue is](https://www.youtube.com/watch?v=U8U2pEyeI6E) - JJ Asghar
- :new: [Linux After Dark – Episode 07](https://linuxafterdark.net/linux-after-dark-episode-07/) - the hosts try silverblue and did an episode on their experiences. 
- :new: [Fedora Silverblue: An Immutable OS](https://www.youtube.com/watch?v=K-FqVWFh01w)
- :new: [What's new in (rpm-)ostree - 2022 edition! - DevConf.CZ 2022](https://www.youtube.com/watch?v=lEDihzhsIjE)

## Distributions

- [Fedora Silverblue](https://silverblue.fedoraproject.org/) - Silverblue is a variant of Fedora Workstation. It looks, feels and behaves like a regular desktop operating system, and the experience is similar to what you find with using a standard Fedora Workstation.
  - [Development on Fedora Silverblue and Fedora Kinoite](https://tim.siosm.fr/blog/2021/12/10/fedora-kinoite-silverblue-dev-guide/#development-using-flatpak)
- [Fedora Kinoite](https://kinoite.fedoraproject.org/) - Similar to Silverblue, but based on KDE.
- [openSUSE MicroOS](https://microos.opensuse.org/) - a variant of openSUSE Tumbleweed and serves as a base of openSUSE Kubic, a Container as a Service platform.
- [NixOS](https://nixos.org/) - a Linux distribution based on Nix package manager
- [Guix System](https://guix.gnu.org/) - a Linux distribution based on the Guix package manager based on Nix
- [EndlessOS](https://endlessos.com/home/) - A Debian derivative distribution with a read-only root filesystem managed by OSTree and Flatpak for application delivery and update
- [rlxos](https://rlxos.dev/) - A immutable, independent general-purpose distribution with primary focus on single file per application.
- [carbonOS](https://carbon.sh/) - An open operating system designed from the ground-up to be intuitive and robust. The [blog post](https://carbon.sh/blog/2021/11/25/release.html) explains the goals

## Tools

- [Toolbx](https://github.com/containers/toolbox) - Tool for containerized command line environments on Linux 
- [Distrobox](https://github.com/89luca89/distrobox) - Tool for containerized command line environments on Linux, distribution agnostic, supports a wide variety of containers , works both with podman and docker - This is a great tool to start with on your existing distro to learn working with day-to-day container workflows.
  - [Integrate VSCode and Distrobox](https://distrobox.privatedns.org/posts/integrate_vscode_distrobox.html) 
- [silverblue-nix](https://gitlab.com/ahayzen/silverblue-nix) - Andrew Hayzen's steps for getting nix working on Fedora Silverblue. 
- [podman](https://podman.io/) - Podman is a daemonless container engine for developing, managing, and running OCI Containers on your Linux System.
  - [gnome-shell-extension-containers](https://github.com/rgolangh/gnome-shell-extension-containers) - This neat extension lets you see what containers you have, start/stop/restart, pause, and shell into them right from the notification area.
  - [Podman desktop companion](https://iongion.github.io/podman-desktop-companion/) - graphical management of your desktop containers
- [libostree](https://github.com/ostreedev/ostree) - Operating system and container binary deployment and upgrades 
- [Toolbox Visual Studio Code Integration](https://github.com/owtaylor/toolbox-vscode) -  Toolbox Visual Studio Code integration 
- [Endless OSTree Builder](https://github.com/dbnicholson/deb-ostree-builder) - Stripped down Endless ostree builder for Debian 
- [Flatpak](https://flatpak.org/) - a utility for software deployment and package management for Linux. It is advertised as offering a sandbox environment in which users can run application software in isolation from the rest of the system.
- [ChromiumOS](https://www.chromium.org/chromium-os/chromiumos-design-docs/filesystem-autoupdate/) - Good design document on how Chromium implements its autoupdate mechanism
- [osbuilder](https://www.osbuild.org/) - Build-Pipelines for Operating System Artifacts
  - [How to: Image Builder + OSTree + Anaconda](https://www.osbuild.org/news/2020-06-01-how-to-ostree-anaconda.html)  
  - [osbuild user guide](https://www.osbuild.org/guides/user-guide/user-guide.html)

## Configs from the Community

:new: If you're automating the config on systems like this please PR your config to share:

- [ostree-pitti-workstation](https://github.com/martinpitt/ostree-pitti-workstation) - Fedora minimal sway developer desktop
- [zepyros-dev's config](https://github.com/zephyros-dev/silverblue-config)
- [JayDoubleau's config (ansiblue)](https://github.com/JayDoubleu/ansiblue)
- [castrojo's config (ublue)](https://github.com/castrojo/ublue) - A familiar(ish) Ubuntu desktop for Fedora Silverblue. 
- :new: [ansible-silverblue](https://github.com/j1mc/ansible-silverblue) - Jim Campbell's ansible playbook for silverblue
- :new: [Sodalite: A Pantheon Experience for Silverblue](https://github.com/electricduck/sodalite)


## Tips

- [Using Automatic Updates on Fedora Silverblue](https://miabbott.github.io/2018/06/13/rpm-ostree-automatic-updates.html)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first. We need more nix resources so if you have good ones please consider PRing one.

If you don't know how to use git then file an issue and leave a link, I'll integrate it into the list!
