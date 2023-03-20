# nix-uninstallers
nix uninstallation scripts.

This is what is being automated for the regular uninstall: https://nixos.org/manual/nix/stable/installation/installing-binary.html#uninstalling

[Nix installation scripts with selinux](https://github.com/dnkmmr69420/nix-with-selinux)


## Scripts

### Regular uninstaller

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/nix-uninstallers/main/regular-uninstaller.sh && chmod a+x ./regular-uninstaller.sh && ./regular-uninstaller.sh ; rm ./regular-uninstaller.sh
```

### Silverblue uninstaller

```bash
wget https://raw.githubusercontent.com/dnkmmr69420/nix-uninstallers/main/silverblue-nix-uninstaller.sh && chmod a+x ./silverblue-nix-uninstaller.sh && ./silverblue-nix-uninstaller.sh ; rm ./silverblue-nix-uninstaller.sh
```
