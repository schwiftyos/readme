# Readme

## Table of Contents

- [Philosophy](#philosophy)
  - [Software Engineering](#software-engineering)
- [Pricing](#pricing)
- [Features](#features)
- [Decentralization](#decentralization)
- [Privacy](#privacy)
  - [Permissions](#permissions)
- [Security](#security)
- [Machine Learning Integrations](#aillm)
- [Under the hood](#under-the-hood)

## Philosophy

"Its **my** system"

It should work on any system, independent of architecture. You control every aspect of it. You can still game on it.

### Software Engineering

This OS will have a central system directory where builds, and their outputs, will reside. This reduces overall disk usage and saves space. You only need one version of the dependencies installed on your system to work with them. This also enables powerful dynamic linking, further reducing program sizes and saving disk space. Does not only apply to Swift.

Native support for IoT, robotics, embedded.

## Pricing

Its free (and open source!).

## Features

- Arch/FreeBSD based (best performance and control)
- Open Source
- Architecture agnostic
- Best Linux file system on the market
- Elevated and streamlined developer experience
- Application permissions
- Can have multiple versions of the same program installed at the same time
- Advanced System Search (similar to Spotlight on macOS)
- Continuity with other systems (sync calendars, contacts, messages, etc)
- App Store
- Widgets
- Keyboard shortcuts
- Decentralized services
- Secure payment system
- Opt-in machine learning features

## Decentralization

"Plays well with others"

Decentralization is a key part in making it play well with others. It will not favorite, lock-in or lock-down certain features from one source.

## Privacy

"You're not allowed to do that"

Privacy is a human right. Your data is your own and up to you on how it is used/shared.

See more about [permissions](#permissions).

### Permissions

Application and System Permissions will be a big part of this OS. This allows the user full control over their system and to inform them about what programs have what permissions.

> **Note:**
>
> You can help us work on this system at [`schwiftyos/schwifty-permmissions`](https://github.com/schwiftyos/schwifty-permmissions)

## Security

The OS is mainly targeting the Swift Programming Language, which is a memory-safe language. The Permissions system prevents processes (and programs) to access unauthorized resources, in short sandboxing them to a user's preference.

> **Technical Note:**
> 
> Memory-safe languages may still encounter leaks and are not guaranteed to be free of data races and may overflow the allocated stack or memory heap. Memory Errors are rare but do exist and can happen.

## Machine Learning Integrations <a name="aillm"></a>

Machine learning features are opt-in. We recognize they are powerful tools, but they should also be used when appropriate. They can be tightly woven into the OS and we will add security measures to prevent unauthorized behavior. Additionally, we want to add accessible interfaces to applications to simplify and enhance model interactions and support general automations instead of having them find where to click on the screen hiding unintentional data from the models by default so that you don’t lose functionality from a supposedly unrelated feature being disabled.

## Under the hood

- File System: Undecided
  - Contenders (listed by most likely to be chosen)
    - OpenZFS
    - ext4
    - Btrfs
- Kernel: Undecided
  - Contenders (listed by most likely to be chosen)
    - Arch Linux (patched)
    - FreeBSD (patched)
    - Zircon (patched)
    - custom Swift
- Display Server / Window Manager: Undecided
  - Contenders (listed by most likely to be chosen)
    - KDE Plasma
    - XFCE
    - Hyprland
    - a Swift UI library

Garuda Linux was mentioned.
