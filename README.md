# Digits — Experimental binaries

> # ⚠️ INSTALL AT YOUR OWN RISK
>
> **This software requires substantial reductions in macOS security, including SIP disabled, Permissive Security and an unsigned kernel extension. Development caused crashes, freezes and macOS reinstalls. Back up first. It is provided as is, without warranty; you accept responsibility for installation, security changes and recovery. Read the full risk notice before downloading or installing.**

## Installation guide

**[Read the full illustrated installation guide](MacOS-27.3/INSTALL.md)** — requirements, security preparation, approval screenshots, installation, Tester, rebinding, uninstall and troubleshooting. The guide is public; only the binaries require the archive password.

## Password-protected download

**[Digits for macOS 27.3 — encrypted ZIP](MacOS-27.3/Digits-macOS-27.3.zip)** contains the complete reference release: Digits Installer 0.1.4.dmg, Digits 0.2.7, Digits Touch 0.1.6, Digits Driver 0.2.4, illustrated guides, screenshots, compatibility information and SHA-256 checksums. No unprotected binaries are published alongside it.

> ## OWNER REPACKAGING AND PASSWORD REQUIRED
>
> **Contact the repository owner to confirm your Mac’s compatibility, arrange provisioning and repackaging, and obtain the archive password. These reference binaries will not work on another, unregistered Mac without updated provisioning profiles, re-signing and repackaging. Access to the archive or its password does not authorize another Mac.**

Extract the archive into the `Releases` root to restore the `MacOS-27.3/` folder and its original paths. Read the [installation guide](MacOS-27.3/INSTALL.md), including its risk notice and private tester provisioning instructions, before installing. The enclosed DMG is the single offline installer; standalone packages are also included for reference.

**This is not a general macOS 27.3 release.** The Driver is pinned to one exact tested Darwin 27.3.0 kernel and USB controller/route. Development provisioning limits the app and Touch to registered Macs. macOS 27.2, 27.0 and 26 builds are not published; compile experiments do not establish compatibility.

[Source repository](https://github.com/Andre-s-World/digits). No Apple approval or notarization is claimed.
