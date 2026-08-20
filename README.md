# Awesome wayland with stars

###

<h1 align="center">
  <samp style="color: #ffffff; background-color: #ffbc00;">Awesome Wayland</samp>

[![Link Check](https://github.com/rcalixte/awesome-wayland/actions/workflows/link_check.yml/badge.svg?branch=master)](https://github.com/rcalixte/awesome-wayland/actions/workflows/link_check.yml) ⭐ 1,550 | 🐛 4 | 📅 2026-08-15

</h1>

A curated list of [Wayland](https://gitlab.freedesktop.org/wayland/wayland) resources. Please investigate these projects on your own before fully committing to them!

This repository is a hard fork of [natpen/awesome-wayland](https://github.com/natpen/awesome-wayland) ⚠️ Archived since it was archived on Oct. 17, 2023.

There are no current plans to apply to the [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 498,096 | 🐛 105 | 📅 2026-08-18 project for inclusion.

> \[!NOTE]
> If you want to contribute, please read [this](https://github.com/rcalixte/awesome-wayland/blob/master/.github/CONTRIBUTING.md) ⭐ 1,550 | 🐛 4 | 📅 2026-08-15.

## SCOPE

> \[!IMPORTANT]
> The scope of this repository aims to capture applications, libraries, etc. that are **designed** to support the Wayland ecosystem. This does not include existing applications that have implemented support for Wayland or applications that only invoke Wayland-based applications. That list is being maintained at [mpsq/arewewaylandyet](https://github.com/mpsq/arewewaylandyet) ⭐ 283 | 🐛 83 | 🌐 HTML | 📅 2024-07-11 which is the repository for [arewewaylandyet.com](https://arewewaylandyet.com). An updated list is also available at [gianklug/wearewaylandnow](https://github.com/gianklug/wearewaylandnow) ⭐ 84 | 🐛 19 | 🌐 HTML | 📅 2026-08-05 which is the repository for [wearewaylandnow.com](https://wearewaylandnow.com).

## TABLE OF CONTENTS

* [SCOPE](#scope)
* [TABLE OF CONTENTS](#table-of-contents)
* [BINDINGS](#bindings)
* [BREAK NOTIFIERS](#break-notifiers)
* [BRIGHTNESS CONTROL](#brightness-control)
* [CLIPBOARD MANAGERS](#clipboard-managers)
* [COMPOSITORS](#compositors)
* [DISPLAY CONFIGURATION](#display-configuration)
* [EMULATION](#emulation)
* [IMAGE VIEWING](#image-viewing)
* [LAUNCHERS](#launchers)
* [LIBRARIES](#libraries)
* [NOTIFICATIONS](#notifications)
* [ON-SCREEN KEYBOARDS](#on-screen-keyboards)
* [REFERENCE APPLICATIONS](#reference-applications)
* [SCREEN LOCKING](#screen-locking)
* [SCREENCASTS](#screencasts)
* [SCREENSHOTS](#screenshots)
* [SESSION MANAGEMENT](#session-management)
* [THEMING](#theming)
* [TOOLS](#tools)
* [WALLPAPER](#wallpaper)
* [WIDGETS (BARS, PANELS, ETC.)](#widgets-bars-panels-etc)
* [WINDOW MANAGERS](#window-managers)

## BINDINGS

These are language-specific bindings for use with Wayland development.

* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [pywayland](https://github.com/flacjacket/pywayland) ⭐ 102 | 🐛 15 | 🌐 Python | 📅 2026-08-15 - A wrapper to the libwayland library
* ![Odin](https://img.shields.io/badge/odin-3882d2?style=plastic\&logo=odin\&logoColor=ffffff) [odin-wayland](https://github.com/yasinkaraaslan/odin-wayland) ⭐ 46 | 🐛 0 | 🌐 Odin | 📅 2026-07-25 - Bindings for creating Wayland clients
* ![Java](https://img.shields.io/badge/java-%23ffffff.svg?style=plastic\&logo=openjdk\&logoColor=%23000000) [wlroots4j](https://github.com/klozovin/nylon/tree/master/wlroots4j) ⭐ 5 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-03 - Bindings for wlroots

## BREAK NOTIFIERS

* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Ianny](https://github.com/zefr0x/ianny) ⭐ 221 | 🐛 7 | 🌐 Rust | 📅 2026-01-07 - Periodically informs user to take breaks by keeping track of usage patterns

## BRIGHTNESS CONTROL

No Wayland-specific requirements, so you can use your Xorg solution of choice to control screen brightness, like [brightnessctl](https://github.com/Hummer12007/brightnessctl) ⭐ 1,256 | 🐛 24 | 🌐 C | 📅 2024-12-16, [brillo](https://gitlab.com/cameronnemo/brillo), or just directly manipulate `/sys/class/backlight`.

* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [wluma](https://github.com/max-baz/wluma) ⭐ 932 | 🐛 1 | 🌐 Rust | 📅 2026-08-19 - A tool for wlroots-based compositors that automatically adjust screen brightness based on screen contents and ambient light
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Clight](https://github.com/FedeDP/Clight) ⭐ 792 | 🐛 31 | 🌐 C | 📅 2026-03-04 - Day/night gamma adjustments for Wayland compositors supporting `wlr-gamma-control-unstable-v1`; automatic screen backlight calibration to match ambient brightness using either webcam or ambient light sensor devices; screen dimming
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Luminance](https://github.com/sidevesh/Luminance) ⭐ 177 | 🐛 11 | 🌐 C | 📅 2026-08-09 - A simple GTK application to control brightness of displays including external displays supporting DDC/CI
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wl-gammactl](https://github.com/mischw/wl-gammactl) ⭐ 66 | 🐛 11 | 🌐 C | 📅 2024-08-05 - A GTK application to set contrast, brightness, and gamma using the `wlr-gamma-control` protocol
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [yabd](https://github.com/tbrugere/yabd) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-05-31 - A simple brightness daemon compatible with Wayland compositors
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Gammastep](https://gitlab.com/chinstrap/gammastep) - A day/night gamma modifier that adjusts the color temperature of the screen
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlsunset](https://git.sr.ht/~kennylevinsen/wlsunset) - A day/night gamma adjustments for Wayland compositors supporting `wlr-gamma-control-unstable-v1` and `xdg-output-unstable-v1` protocols

## CLIPBOARD MANAGERS

* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wl-clipboard](https://github.com/bugaevc/wl-clipboard) ⭐ 2,407 | 🐛 70 | 🌐 C | 📅 2026-08-06 - Command-line copy/paste utilities for Wayland
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [cliphist](https://github.com/sentriz/cliphist) ⭐ 1,523 | 🐛 13 | 🌐 Go | 📅 2026-06-08 - A clipboard history manager for Wayland
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [clapboard](https://github.com/bjesus/clapboard) ⭐ 82 | 🐛 1 | 🌐 Rust | 📅 2025-10-06 - A clipboard manager with support for images and saved entries
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wayclip](https://github.com/noocsharp/wayclip) ⭐ 32 | 🐛 0 | 🌐 C | 📅 2025-09-22 - A Wayland clipboard utility implementing the `wlr-data-control-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [gemclip](https://codeberg.org/novenary/gemclip) - A simple clipboard utility for Wayland implementing the `wlr-data-control-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlclipper](https://codeberg.org/baltazar/wlclipper) - A wlroots-based clipboard manager with persistence and synchronization
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlsnarf](https://codeberg.org/notchoc/wlsnarf) - A highly scriptable clipboard tool for wlroots-based compositors implementing the `wlr-data-control-unstable-v1` protocol; includes a filesystem-based clipboard manager daemon with persistence

## COMPOSITORS

* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Hyprland](https://github.com/hyprwm/Hyprland) ⭐ 37,979 | 🐛 194 | 🌐 C++ | 📅 2026-08-19 - A dynamic tiling Wayland compositor that doesn't sacrifice on its looks
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [niri](https://github.com/niri-wm/niri) ⭐ 27,035 | 🐛 480 | 🌐 Rust | 📅 2026-08-19 - A Smithay-based scrollable tiling Wayland compositor
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [sway](https://github.com/swaywm/sway) ⭐ 17,253 | 🐛 1,377 | 🌐 C | 📅 2026-07-31 - An i3-compatible Wayland compositor
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [gamescope](https://github.com/ValveSoftware/gamescope) ⭐ 4,998 | 🐛 943 | 🌐 C++ | 📅 2026-08-20 - A wlroots-based Wayland compositor designed for SteamOS
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [mangowm](https://github.com/mangowm/mango) ⭐ 3,485 | 🐛 215 | 🌐 C | 📅 2026-08-20 - A dwl-inspired Wayland compositor with lightweight animations and customizable layouts
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Wayfire](https://github.com/WayfireWM/wayfire) ⭐ 3,034 | 🐛 115 | 🌐 C++ | 📅 2026-08-11 - A 3D wlroots-based Wayland compositor inspired by Compiz
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [labwc](https://github.com/labwc/labwc) ⭐ 2,740 | 🐛 295 | 🌐 C | 📅 2026-08-14 - A wlroots-based stacking compositor for Wayland, inspired by openbox
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [SwayFX](https://github.com/wlrfx/swayfx) ⭐ 2,339 | 🐛 163 | 🌐 C | 📅 2026-08-16 - Sway, but with eye candy
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Cage](https://github.com/cage-kiosk/cage) ⭐ 2,015 | 🐛 123 | 🌐 C | 📅 2026-08-18 - A Wayland compositor that runs a single application in maximized mode, particularly suitable for kiosk applications
* ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=plastic\&logo=javascript\&logoColor=%23f7df1e) [Greenfield](https://github.com/udevbe/greenfield) ⭐ 1,265 | 🐛 23 | 🌐 TypeScript | 📅 2025-11-02 - An HTML5 Wayland compositor that runs directly in the browser
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [cosmic-comp](https://github.com/pop-os/cosmic-comp) ⭐ 816 | 🐛 944 | 🌐 Rust | 📅 2026-08-20 - A Smithay-based Wayland compositor designed for the COSMIC desktop environment
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [miracle-wm](https://github.com/miracle-wm-org/miracle-wm) ⭐ 793 | 🐛 42 | 🌐 C++ | 📅 2026-08-12 - A Mir-based tiling Wayland compositor
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [kiwmi](https://github.com/buffet/kiwmi) ⭐ 764 | 🐛 11 | 🌐 C | 📅 2025-08-14 - A fully programmable Wayland compositor
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Jay](https://github.com/mahkoh/jay) ⭐ 699 | 🐛 96 | 🌐 Rust | 📅 2026-08-19 - A tiling Wayland compositor inspired by i3wm
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [pinnacle](https://github.com/pinnacle-comp/pinnacle) ⭐ 627 | 🐛 44 | 🌐 Rust | 📅 2026-06-27 - A Smithay-based Wayland compositor inspired by AwesomeWM
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [scroll](https://github.com/dawsers/scroll) ⭐ 582 | 🐛 8 | 🌐 C | 📅 2026-08-20 - A wlroots-based scrollable Wayland compositor forked from sway with a layout similar to PaperWM and niri
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Waybox](https://github.com/wizbright/waybox) ⭐ 536 | 🐛 12 | 🌐 C | 📅 2026-01-03 - An openbox clone on Wayland
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Vivarium](https://github.com/inclement/vivarium) ⭐ 423 | 🐛 36 | 🌐 C | 📅 2023-09-22 - A dynamic tiling Wayland compositor using wlroots, with desktop semantics inspired by xmonad
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlmaker](https://github.com/phkaeser/wlmaker) ⭐ 422 | 🐛 21 | 🌐 C | 📅 2026-08-17 - A Wayland compositor inspired by Window Maker
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) ![Lisp](https://img.shields.io/badge/lisp-%23000.svg?style=plastic\&logo=lisp\&logoColor=fff) [mahogany](https://github.com/stumpwm/mahogany) ⭐ 381 | 🐛 63 | 🌐 Common Lisp | 📅 2026-08-15 - A StumpWM-like Wayland compositor
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Cagebreak](https://github.com/project-repo/cagebreak) ⭐ 374 | 🐛 4 | 🌐 C | 📅 2026-06-13 - A Wayland tiling compositor inspired by Ratpoison
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [fht-compositor](https://github.com/nferhat/fht-compositor) ⭐ 276 | 🐛 23 | 🌐 Rust | 📅 2026-08-13 - A dynamic tiling Wayland compositor
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Liri Shell](https://github.com/lirios/shell) ⭐ 248 | 🐛 35 | 🌐 C++ | 📅 2024-02-11 - A convergent shell for desktops, phones, and tablets
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [way-shell](https://github.com/ldelossa/way-shell) ⭐ 196 | 🐛 13 | 🌐 C | 📅 2026-02-21 - A desktop shell based on GTK 4 for wlroots-based Wayland compositors
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [CwC](https://github.com/Cudiph/cwcwm) ⭐ 182 | 🐛 11 | 🌐 C | 📅 2026-08-17 - A highly configurable wlroots-based tiling window manager, inspired by AwesomeWM
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wayward](https://github.com/varmd/wayward) ⭐ 124 | 🐛 3 | 🌐 C | 📅 2026-07-20 - A lightweight desktop shell compatible with Weston
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Miriway](https://github.com/Miriway/Miriway) ⭐ 105 | 🐛 18 | 🌐 C++ | 📅 2026-08-17 - A Mir-based Wayland compositor
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [treeland](https://github.com/linuxdeepin/treeland) ⭐ 74 | 🐛 94 | 🌐 C++ | 📅 2026-08-20 - A wlroots-based Wayland compositor also based on Qt Quick
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [Nyctal](https://github.com/s-rah/nyctal) ⭐ 56 | 🐛 1 | 🌐 Go | 📅 2024-11-24 - A tiny, minimal-dependency Wayland compositor
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [foxwhale](https://github.com/malcolmstill/foxwhale) ⭐ 42 | 🐛 18 | 🌐 Zig | 📅 2024-10-20 - A tiling Wayland compositor based on wlroots
* ![Nim](https://img.shields.io/badge/nim-%23171921.svg?style=plastic\&logo=nim\&logoColor=ffe953) [gogh](https://github.com/xTrayambak/gogh) ⭐ 39 | 🐛 2 | 🌐 C | 📅 2025-05-01 - A lightweight Wayland compositor using Louvre
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [LaikaWM](https://github.com/ianmartinez/laikawm) ⭐ 36 | 🐛 1 | 🌐 C++ | 📅 2020-10-01 - A lightweight compositor for Wayland inspired by IceWM and Fluxbox
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [kawa](https://github.com/DeedleFake/kawa) ⭐ 34 | 🐛 4 | 🌐 Go | 📅 2026-02-13 - A wlroots-based Wayland compositor inspired by Plan 9's Rio
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [tinywl+](https://github.com/keshto/tinywl_plus) ⭐ 32 | 🐛 1 | 🌐 C | 📅 2023-04-10 - A stacking Wayland compositor based on tinywl and a great starting place for compositor development
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Magpie v1](https://github.com/buddiesofbudgie/magpie/tree/v1) ⭐ 27 | 🐛 10 | 🌐 C | 📅 2025-03-25 - A wlroots-based Wayland compositor designed for the Budgie desktop environment
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Woodland](https://github.com/DiogenesN/woodland) ⭐ 25 | 🐛 0 | 🌐 C | 📅 2026-06-12 - A minimal and lightweight wlroots-based stacking compositor, inspired by Wayfire and TinyWL
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [doors](https://github.com/dy-tea/doors) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2026-08-19 - A Wayland compositor with floating, tiling, and scrolling layouts, inspired by bspwm
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Hopalong](https://github.com/iridescent-desktop/hopalong) ⭐ 22 | 🐛 7 | 🌐 C | 📅 2022-11-13 - A simple Wayland compositor with a feature set comparable to XFWM
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [pudu](https://github.com/vodkanull/pudu) ⭐ 22 | 🐛 4 | 🌐 C | 📅 2026-08-09 - A minimal tiling Wayland compositor
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [turtile](https://github.com/migueldeoleiros/turtile) ⭐ 15 | 🐛 7 | 🌐 C | 📅 2024-11-29 - A simple and customizable wlroots-based tiling compositor
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [fluxland](https://github.com/ecliptik/fluxland) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2026-03-04 - A lightweight Wayland compositor inspired by Fluxbox
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wless](https://github.com/qaqland/wless) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2025-11-09 - A wlroots-based window-less Wayland compositor
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [Mezzaluna](https://github.com/MezzalunaWM/Mezzaluna) ⭐ 10 | 🐛 18 | 🌐 Zig | 📅 2026-08-12 - A minimal wlroots-based Wayland compositor configured using Lua
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [LabFyre](https://github.com/FyreX-opensource-design/labFyre) ⭐ 8 | 🐛 1 | 🌐 C | 📅 2026-03-05 - A wlroots-based modular stacking and tiling Wayland compositor, forked from labwc
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [vwl](https://github.com/wegel/vwl) ⭐ 7 | 🐛 5 | 🌐 C | 📅 2026-04-15 - A simple wlroots-based Wayland compositor originally forked from dwl
* ![V](https://img.shields.io/badge/v-%23fff.svg?style=plastic\&logo=v\&logoColor=4a607e) [vwm](https://github.com/dy-tea/vwm) ⭐ 6 | 🐛 0 | 🌐 V | 📅 2026-01-01 - A wlroots-based Wayland compositor
* ![Kotlin](https://img.shields.io/badge/kotlin-%23ffffff.svg?style=plastic\&logo=kotlin\&logoColor=%237f52ff) [nylon-compositor](https://github.com/klozovin/nylon/tree/master/compositor) ⭐ 5 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-03 - A minimal wlroots-based Wayland compositor
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [stagen](https://github.com/lidgnulinux/stagen) ⭐ 5 | 🐛 0 | 🌐 C | 📅 2024-01-24 - An experimental wlroots-based Wayland compositor
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [tiley](https://github.com/creamIcec/tiley) ⭐ 5 | 🐛 1 | 🌐 C++ | 📅 2025-09-11 - A customizable tiling Wayland compositor based on Louvre
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [Gabbia](https://github.com/heuer/gabbia) ⭐ 2 | 🐛 9 | 🌐 Python | 📅 2025-03-13 - A Wayland compositor inspired by Cage that runs a single application in maximized mode, particularly suitable for kiosk applications
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [croissant](https://codeberg.org/vyivel/croissant) - A wlroots-based stacking Wayland compositor
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [dwl](https://codeberg.org/dwl/dwl) - A wlroots-based rewrite of DWM for Wayland
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [hikari](https://codeberg.org/thomasadam/hikari) - A wlroots-based stacking Wayland compositor with tiling capabilities, forked from the original hikari
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [IonWL](https://codeberg.org/ideasman42/IonWL) - A manual tiling Smithay-based Wayland compositor inspired by Ion3
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [marshmallow](https://codeberg.org/MrBrownFR/marshmallow) - A Wayland compositor with tablets and phones in mind
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [musa](https://git.sr.ht/~mainiomano/musa) - A Wayland compositor based on wlroots focusing on multiseat functionality
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [newm-atha](https://git.sr.ht/~atha/newm-atha) - A Wayland compositor written with laptops and touchpads in mind
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [river-classic](https://codeberg.org/river/river-classic) - A fork of river 0.3 intended for users who do not want river 0.4+ features and breaking changes
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [river](https://codeberg.org/river/river) - A non-monolithic Wayland compositor
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [tinywl](https://codeberg.org/ifreund/zig-wlroots/src/branch/master/tinywl) - A re-implementation of tinywl
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [vdwl](https://codeberg.org/ionnix/vdwl) - A standalone, minimalist wlroots-based Wayland compositor originally forked from dwl
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [volare](https://codeberg.org/raboof/volare) - A tiling, tabbed Wayland compositor
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Weston](https://gitlab.freedesktop.org/wayland/weston/) - A Wayland compositor designed for correctness, reliability, predictability, and performance
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wio](https://gitlab.com/Rubo/wio) - A wlroots-based Wayland compositor inspired by Plan 9's Rio
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [xerium](https://codeberg.org/xerium-wm/xerium) - A fast and lightweight Wayland compositor

## DISPLAY CONFIGURATION

* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [nwg-displays](https://github.com/nwg-piotr/nwg-displays) ⭐ 1,081 | 🐛 41 | 🌐 Python | 📅 2026-06-01 - An output management utility for sway and Hyprland, inspired by wdisplays and wlay
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [Wallutils](https://github.com/xyproto/wallutils) ⭐ 521 | 🐛 5 | 🌐 Go | 📅 2026-06-04 - A set of utilities to handle monitors, resolutions, wallpapers, and timed wallpapers
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wdisplays](https://github.com/artizirk/wdisplays) ⭐ 284 | 🐛 25 | 🌐 C | 📅 2025-07-25 - A GUI application for configuring displays in wlroots-based compositors implementing the `wlr-output-management-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlay](https://github.com/atx/wlay) ⭐ 123 | 🐛 10 | 🌐 C | 📅 2024-07-02 - Graphical output management for Wayland
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [wayland-displays](https://github.com/heyzec/wayland-displays) ⭐ 18 | 🐛 3 | 🌐 C++ | 📅 2026-08-16 - A GUI and CLI tool for managing display outputs on wlroots-based Wayland compositors implementing the `wlr-output-management-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Kanshi](https://gitlab.freedesktop.org/emersion/kanshi) - A dynamic display configuration tool for Wayland similar to autorandr, usable on Wayland compositors supporting the `wlr-output-management` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [shikane](https://gitlab.com/w0lff/shikane) - A wlroots-based dynamic output configuration tool similar to autorandr, usable on Wayland compositors supporting the `wlr-output-management` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [wayout](https://git.sr.ht/~shinyzenith/wayout) - A simple output management tool for wlroots-based compositors implementing `wlr-output-management-unstable-v1`
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlr-randr](https://gitlab.freedesktop.org/emersion/wlr-randr) - A utility to manage outputs of wlroots-based Wayland compositors, inspired by xrandr

## EMULATION

* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [Waydroid](https://github.com/waydroid/waydroid) ⭐ 12,018 | 🐛 931 | 🌐 Python | 📅 2026-08-01 - A container-based approach to boot a full Android system on GNU/Linux

## IMAGE VIEWING

* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Swayimg](https://github.com/artemsen/swayimg) ⭐ 704 | 🐛 8 | 🌐 C++ | 📅 2026-08-16 - An image viewer for Sway/Wayland

## LAUNCHERS

* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [walker](https://github.com/abenz1267/walker) ⭐ 2,989 | 🐛 21 | 🌐 Rust | 📅 2026-07-23 - A GTK-based Wayland-native application runner
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [bemenu](https://github.com/Cloudef/bemenu) ⭐ 1,485 | 🐛 94 | 🌐 C | 📅 2025-08-29 - A dynamic menu library and client program inspired by dmenu
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [tofi](https://github.com/philj56/tofi) ⭐ 1,396 | 🐛 117 | 🌐 C | 📅 2024-12-30 - A dynamic menu replacement for dmenu or rofi for wlroots-based Wayland compositors
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Anyrun](https://github.com/anyrun-org/anyrun) ⭐ 1,292 | 🐛 73 | 🌐 Rust | 📅 2026-08-14 - A GTK-based Wayland-native launcher, customizable via CSS
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [Hexecute](https://github.com/m31-galaxy/Hexecute) ⭐ 693 | 🐛 11 | 🌐 C | 📅 2026-06-25 - A gesture-based launcher for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [sirula](https://github.com/DorianRudolph/sirula) ⭐ 562 | 🐛 5 | 🌐 Rust | 📅 2026-05-04 - A simple application launcher for Wayland
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [kickoff](https://github.com/j0ru/kickoff) ⭐ 480 | 🐛 20 | 🌐 Rust | 📅 2026-08-11 - A wlroots-based application launcher
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [yofi](https://github.com/l4l/yofi) ⭐ 439 | 🐛 19 | 🌐 Rust | 📅 2026-04-17 - A minimalistic menu for Wayland-based compositors
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [nwg-launchers](https://github.com/nwg-piotr/nwg-launchers) ⭐ 427 | 🐛 19 | 🌐 C++ | 📅 2024-02-06 - A GTK-based application grid launcher, button bar, and dmenu for Sway with a best effort for other Wayland environments
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [nwg-drawer](https://github.com/nwg-piotr/nwg-drawer) ⭐ 421 | 🐛 32 | 🌐 Go | 📅 2026-03-24 - An application launcher for wlroots-based Wayland compositors implementing the `gtk4-layer-shell` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [dmenu-wayland](https://github.com/nyyManni/dmenu-wayland) ⭐ 215 | 🐛 16 | 🌐 C | 📅 2023-12-22 - A wlroots-based dynamic menu for Wayland
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [wldash](https://github.com/kennylevinsen/wldash) ⭐ 204 | 🐛 13 | 🌐 Rust | 📅 2025-05-08 - A dashboard, launcher, or control panel for Wayland, using the `wlr-layer-shell-unstable-v1` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [sysmenu](https://github.com/System64fumo/sysmenu) ⭐ 121 | 🐛 2 | 🌐 C++ | 📅 2026-05-14 - A simple program launcher for wlroots-based Wayland compositors, implementing the `gtk4-layer-shell` protocol
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [nwg-menu](https://github.com/nwg-piotr/nwg-menu) ⭐ 85 | 🐛 12 | 🌐 Go | 📅 2025-06-06 - A simple menu implementing the `gtk3-layer-shell` protocol
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [mounch](https://github.com/chmouel/mounch) ⭐ 58 | 🐛 0 | 🌐 Python | 📅 2026-06-22 - A simple wofi/rofi launcher configured via YAML
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Mauncher](https://github.com/mortie/mauncher) ⭐ 42 | 🐛 3 | 🌐 C | 📅 2021-11-19 - A GTK-based alternative to dmenu for Wayland which supports display scaling
* ![Nim](https://img.shields.io/badge/nim-%23171921.svg?style=plastic\&logo=nim\&logoColor=ffe953) [basket](https://github.com/xTrayambak/basket) ⭐ 17 | 🐛 0 | 🌐 Nim | 📅 2024-12-04 - A minimal application launcher for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [lawnch](https://github.com/hoppxi/lawnch) ⭐ 12 | 🐛 0 | 🌐 C++ | 📅 2026-03-25 - A lightweight extensible launcher for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [diowapplauncher](https://github.com/DiogenesN/diowapplauncher) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2025-12-02 - A simple application launcher for Wayland compositors implementing the `xdg-shell` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [diowmenu](https://github.com/DiogenesN/diowmenu) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2024-09-07 - A simple quick launch menu for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [waylauncher](https://github.com/tomipkoskinen/waylauncher) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2024-08-12 - A GTK-based application launcher implementing the `gtk4-layer-shell` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [emenu](https://codeberg.org/fbushstone/emenu) - An efficient menu for wlroots-based Wayland compositors
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [fuzzel](https://codeberg.org/dnkl/fuzzel) - An application launcher for wlroots-based Wayland compositors, similar to rofi's `drun` mode
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [gmenu](https://codeberg.org/tslocum/gmenu) - A desktop application launcher
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [LavaLauncher](https://git.sr.ht/~leon_plickat/lavalauncher) - A simple launcher panel for Wayland desktops
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [mew](https://codeberg.org/sewn/mew) - A dmenu-like dynamic menu for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [waypiedock](https://gitlab.com/Arnaudv6/waypiedock) - A launcher dock, in the shape of a pie, under the mouse
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wmenu](https://codeberg.org/adnano/wmenu) - A dynamic menu for Sway and wlroots-based compositors inspired by dmenu

## LIBRARIES

* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [smithay](https://github.com/Smithay/smithay) ⭐ 3,182 | 🐛 255 | 🌐 Rust | 📅 2026-08-17 - A compositor library for Wayland
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Mir](https://github.com/canonical/mir) ⭐ 778 | 🐛 411 | 🌐 C++ | 📅 2026-08-20 - A set of libraries for building Wayland-based shells
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [swc](https://github.com/michaelforney/swc) ⭐ 756 | 🐛 23 | 🌐 C | 📅 2026-03-26 - A small Wayland compositor implemented as a library
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Louvre](https://github.com/CuarzoSoftware/Louvre) ⭐ 683 | 🐛 8 | 🌐 C++ | 📅 2026-07-20 - A library designed for building Wayland compositors in C++
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [client-toolkit](https://github.com/Smithay/client-toolkit) ⭐ 432 | 🐛 73 | 🌐 Rust | 📅 2026-07-29 - A toolkit for writing Wayland clients in Rust
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [gtk-layer-shell](https://github.com/wmww/gtk-layer-shell) ⭐ 384 | 🐛 8 | 🌐 C | 📅 2026-08-16 - A library to create panels and other desktop components for Wayland using GTK 3 and the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [gtk4-layer-shell](https://github.com/wmww/gtk4-layer-shell) ⭐ 329 | 🐛 5 | 🌐 C | 📅 2026-08-16 - A library to create panels and other desktop components for Wayland using GTK 4 and the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wld](https://github.com/michaelforney/wld) ⭐ 116 | 🐛 7 | 🌐 C | 📅 2026-08-11 - A drawing library that targets Wayland
* ![OCaml](https://img.shields.io/badge/ocaml-%23ededed.svg?style=plastic\&logo=ocaml\&logoColor=ec670f) [ocaml-wayland](https://github.com/talex5/ocaml-wayland) ⭐ 93 | 🐛 5 | 🌐 OCaml | 📅 2026-07-08 - An implementation of the Wayland protocol in OCaml
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [waylib](https://github.com/vioken/waylib) ⭐ 56 | 🐛 36 | 🌐 C++ | 📅 2026-08-11 - A Wayland compositor development library based on wlroots and Qt Quick
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [layer-shell-qt](https://github.com/KDE/layer-shell-qt) ⭐ 53 | 🐛 0 | 🌐 C++ | 📅 2026-08-11 - A Qt-based library to allow applications to use the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Swingby](https://github.com/aspschn/swingby) ⭐ 46 | 🐛 1 | 🌐 C | 📅 2026-08-20 - A small GUI library for Wayland client programming
* ![Scheme](https://img.shields.io/badge/scheme-%23000.svg?style=plastic) [guile-wayland](https://github.com/guile-wayland/guile-wayland) ⭐ 20 | 🐛 9 | 🌐 Scheme | 📅 2026-01-09 - A library that provides access to the Wayland protocol for applications written in GNU Guile Scheme
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [way-z](https://github.com/psnszsn/way-z) ⭐ 18 | 🐛 0 | 🌐 Zig | 📅 2026-03-13 - A client library and widget toolkit for wlroots-based Wayland applications written in Zig
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Wrapland](https://github.com/winft/wrapland) ⭐ 12 | 🐛 28 | 🌐 C++ | 📅 2024-10-09 - A Qt-based wrapper library for the libwayland client and server APIs
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [glace](https://github.com/Fabric-Development/glace) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2026-08-19 - A GTK-based library that aids in the management of Wayland clients such as docks and desktop widgets
* ![Dart](https://img.shields.io/badge/dart-29b6f6?style=plastic\&logo=dart\&logoColor=01579b) [wayland-dart](https://github.com/kingwill101/wayland-dart) ⭐ 8 | 🐛 0 | 🌐 Dart | 📅 2026-08-15 - A Dart implementation of the Wayland client protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wleaf](https://github.com/markbolhuis/wleaf) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-02-05 - A C23 abstraction library for writing Wayland clients
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [shoyu](https://github.com/Midstall/shoyu) ⭐ 0 | 🐛 2 | 🌐 C | 📅 2025-01-02 - A framework for wlroots-based, GTK-based Wayland implementations
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [shimizu](https://git.klaji.dev/klaji/shimizu) - A library for interfacing with the Wayland protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wink](https://codeberg.org/lirr-govel/wink) - A library for creating windows responsive to input events
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlroots](https://gitlab.freedesktop.org/wlroots/wlroots/) - Pluggable, composable, and unopinionated modules for building a Wayland compositor
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [zig-wlroots](https://codeberg.org/ifreund/zig-wlroots) - Bindings to wlroots for Zig for developing Wayland compositors and clients

## NOTIFICATIONS

* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [dunst](https://github.com/dunst-project/dunst) ⭐ 5,568 | 🐛 123 | 🌐 C | 📅 2026-08-11 - A highly configurable and lightweight notification daemon
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [mako](https://github.com/emersion/mako) ⭐ 3,228 | 🐛 135 | 🌐 C | 📅 2026-06-30 - A lightweight notification daemon for Wayland implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Vala](https://img.shields.io/badge/vala-%237b6ca3.svg?style=plastic\&logo=vala\&logoColor=fff) [SwayNotificationCenter](https://github.com/ErikReider/SwayNotificationCenter) ⭐ 2,559 | 🐛 110 | 🌐 Vala | 📅 2026-06-25 - A simple notification daemon with a GTK GUI for notifications and the control center implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [SwayOSD](https://github.com/ErikReider/SwayOSD) ⭐ 1,291 | 🐛 30 | 🌐 Rust | 📅 2026-06-22 - A GTK-based OSD window for common actions like volume and Caps Lock
* ![Vala](https://img.shields.io/badge/vala-%237b6ca3.svg?style=plastic\&logo=vala\&logoColor=fff) [Avizo](https://github.com/heyjuvi/avizo) ⭐ 619 | 🐛 26 | 🌐 Vala | 📅 2025-10-08 - A simple notification daemon, mainly intended to be used for multimedia keys
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [histui](https://github.com/jmylchreest/histui) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2026-08-12 - A themeable notification daemon with TUI and CLI options for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [fnott](https://codeberg.org/dnkl/fnott) - A keyboard-driven and lightweight notification daemon for wlroots-based Wayland compositors
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [luft](https://codeberg.org/marendowski/luft) - A lightweight notification daemon for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Toffi](https://codeberg.org/bootovy/toffi) - A Qt-based notification server for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol

## ON-SCREEN KEYBOARDS

* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wvkbd](https://github.com/jjsullivan5196/wvkbd) ⭐ 455 | 🐛 28 | 🌐 C | 📅 2026-07-24 - An on-screen keyboard for wlroots-based compositors
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [wkeys](https://github.com/ptazithos/wkeys) ⭐ 43 | 🐛 5 | 🌐 Rust | 📅 2026-02-16 - An on-screen keyboard featuring a configurable layout and style for Wayland compositors supporting the `gtk4-layer-shell` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [wf-osk](https://github.com/WayfireWM/wf-osk) ⭐ 32 | 🐛 5 | 🌐 C++ | 📅 2024-03-25 - A very, very basic on-screen keyboard using gtkmm and the `virtual-keyboard-unstable-v1` and `wlr-layer-shell-unstable-v1` protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wshowkeys](https://git.sr.ht/~sircmpwn/wshowkeys) - Displays keypresses on screen on Wayland compositors supporting the `wlr-layer-shell-unstable-v1` protocol

## REFERENCE APPLICATIONS

These are mainly for developers looking for example implementations.

* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [vkwayland](https://github.com/kdchambers/vkwayland) ⭐ 52 | 🐛 0 | 🌐 Zig | 📅 2026-06-06 - A reference application for Vulkan and Wayland
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [wayland-py](https://github.com/aslpavel/wayland-py) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-01-19 - A pure Python implementation of a Wayland client
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [go-wayland](https://github.com/MatthiasKunnen/go-wayland) ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2025-08-21 - A basic implementation of the Wayland protocol
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [zig-wayland](https://codeberg.org/ifreund/zig-wayland) - A basic implementation of the Wayland protocol for developing Wayland compositors and clients, including examples

## SCREEN LOCKING

* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [hyprlock](https://github.com/hyprwm/hyprlock) ⭐ 1,636 | 🐛 188 | 🌐 C++ | 📅 2026-08-11 - A multi-threaded and GPU-accelerated screen locking utility for wlroots-based Wayland compositors implementing the `ext-session-lock-v1` and `wlr-screencopy-unstable-v1` protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [swaylock](https://github.com/swaywm/swaylock) ⭐ 1,214 | 🐛 101 | 🌐 C | 📅 2026-07-09 - A screen locking utility for Wayland which implements the `ext-idle-notify-v1` protocol protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [swaylock-effects](https://github.com/mortie/swaylock-effects) ⭐ 861 | 🐛 61 | 🌐 C | 📅 2023-11-28 - A fork of swaylock which adds, built-in screenshots, image manipulation, and various other effects like blurring
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [swayidle](https://github.com/swaywm/swayidle) ⭐ 755 | 🐛 38 | 🌐 C | 📅 2026-08-17 - An idle management daemon for Wayland which implements the `ext-idle-notify-v1` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [hypridle](https://github.com/hyprwm/hypridle) ⭐ 694 | 🐛 43 | 🌐 C++ | 📅 2026-08-11 - A wlroots-based idle management daemon implementing the `ext-idle-notify-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [gtklock](https://github.com/jovanlanik/gtklock) ⭐ 493 | 🐛 26 | 🌐 C | 📅 2026-02-04 - A GTK-based lockscreen for wlroots-based Wayland compositors using the `wlr-layer-shell-unstable-v1` and `wlr-input-inhibitor` Wayland protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlgblock](https://github.com/AdoPi/wlgblock) ⭐ 173 | 🐛 0 | 🌐 C | 📅 2025-09-20 - An emulator-based screen-locker for Wayland compositors implementing the `ext-session-lock-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [cthulock](https://github.com/FriederHannenheim/cthulock) ⭐ 58 | 🐛 3 | 🌐 Rust | 📅 2025-09-27 - A Slint-based customizable screen-locker for Wayland compositors implementing the `ext-session-lock-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Shaderlock](https://github.com/RobinMcCorkell/shaderlock) ⭐ 29 | 🐛 5 | 🌐 Rust | 📅 2025-09-25 - A wlroots-based screen-locker for Wayland utilizing GPU shaders
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Anvilock](https://github.com/muvilon/anvilock) ⭐ 22 | 🐛 1 | 🌐 C | 📅 2025-07-12 - A simple screen-locker for Wayland compositors that support the `ext-session-lock-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [btrlock](https://codeberg.org/julmajustus/btrlock) - A fast and minimal screen-locker
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [chayang](https://git.sr.ht/~emersion/chayang) - A screen dimmer that can be used to implement a grace period before locking the session
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [waylock](https://codeberg.org/ifreund/waylock) - A small screen-locker for Wayland compositors implementing the `ext-session-lock-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlock](https://codeberg.org/sewn/wlock) - A simple screen-locker for Wayland compositors that support the `ext-session-lock-v1` protocol

## SCREENCASTS

* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Kooha](https://github.com/SeaDve/Kooha) ⭐ 3,483 | 🐛 97 | 🌐 Rust | 📅 2026-07-29 - Minimalistic screen recorder for Wayland sessions implementing the `org.freedesktop.impl.portal.ScreenCast` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [wf-recorder](https://github.com/ammen99/wf-recorder) ⭐ 1,304 | 🐛 55 | 🌐 C++ | 📅 2026-04-12 - A utility program for screen recording of wlroots-based compositors (more specifically, those that support `wlr-screencopy-unstable-v1` and `xdg-output-unstable-v1`)
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [wl-screenrec](https://github.com/russelltg/wl-screenrec) ⭐ 622 | 🐛 29 | 🌐 Rust | 📅 2026-08-10 - A screen recorder for wlroots-based Wayland compositors leveraging DMA-BUF and the DRM and implementing the `wlr-output-management-unstable-v1` and `wlr-screencopy-unstable-v1` protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wl-mirror](https://github.com/Ferdi265/wl-mirror) ⭐ 516 | 🐛 20 | 🌐 C | 📅 2026-08-17 - A simple Wayland output mirror client
* ![Vala](https://img.shields.io/badge/vala-%237b6ca3.svg?style=plastic\&logo=vala\&logoColor=fff) [wayfarer](https://github.com/stronnag/wayfarer) ⚠️ Archived - A screen recorder for GNOME/Wayland/PipeWire implementing the `org.freedesktop.impl.portal.ScreenCast` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [ssr-wlroots](https://github.com/foxcpp/ssr-wlroots) ⭐ 26 | 🐛 4 | 🌐 C++ | 📅 2019-03-16 - A fork of SimpleScreenRecorder with support for wlroots-based compositors (more specifically, those that support `wlr-screencopy-unstable-v1` and `xdg-output-unstable-v1`) - doesn't support recording area selection and has issues with multiple screens
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [Lumina](https://codeberg.org/pparaxan/lumina) - A simple screen recorder for Wayland compositors implementing the `ext-image-capture-source-v1`, `ext-image-copy-capture-v1`, and `xdg-output-unstable-v1` protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlrobs](https://hg.sr.ht/~scoopta/wlrobs) - A plugin for OBS Studio that allows screen capture on wlroots-based Wayland compositors

## SCREENSHOTS

* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Satty](https://github.com/Satty-org/Satty) ⭐ 2,328 | 🐛 80 | 🌐 Rust | 📅 2026-08-18 - A screenshot annotation tool inspired by Swappy and Flameshot
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [swappy](https://github.com/jtheoof/swappy) ⭐ 1,494 | 🐛 49 | 🌐 C | 📅 2025-12-16 - A Wayland-native snapshot editing tool, inspired by Snappy on macOS
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [slurp](https://github.com/emersion/slurp) ⭐ 1,274 | 🐛 51 | 🌐 C | 📅 2026-05-10 - Select a region in a Wayland compositor and print it to the standard output
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Watershot](https://github.com/Kirottu/watershot) ⭐ 212 | 🐛 23 | 🌐 Rust | 📅 2024-06-28 - A simple Wayland-native screenshot tool inspired by Flameshot
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [waysip](https://github.com/waycrate/waysip) ⭐ 30 | 🐛 3 | 🌐 Rust | 📅 2026-08-06 - An area selector for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [haruhishot](https://github.com/Decodetalkers/haruhishot) ⭐ 29 | 🐛 7 | 🌐 Rust | 📅 2026-05-13 - A screenshot utility for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` and `wlr-screencopy-unstable-v1` protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [still](https://github.com/faergeek/still) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2026-08-12 - A tool that freezes the screen until a provided command exits for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` and `wlr-screencopy-unstable-v1` protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [grabit](https://github.com/Creationsss/grabit) ⭐ 22 | 🐛 1 | 🌐 C | 📅 2026-08-11 - A screenshot, screen-recording, and OCR tool for wlroots-based Wayland compositors implementing the `wlr-data-control-unstable-v1`, `wlr-layer-shell-unstable-v1`, and `wlr-screencopy-unstable-v1` protocols
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [samurai-select](https://github.com/Samudevv/samurai-select) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2026-03-19 - A screen selection tool for wlroots-based Wayland compositors implementing `wlr-layer-shell-unstable-v1`
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [Seto](https://github.com/r0chd/Seto) ⭐ 9 | 🐛 2 | 🌐 Zig | 📅 2025-04-30 - A hardware-accelerated and keyboard-driven screen selection tool implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Weye](https://github.com/Yakkhini/Weye) ⭐ 5 | 🐛 0 | 🌐 Rust | 📅 2022-06-23 - A lightweight screenshot tool for sway users
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [cullpp](https://codeberg.org/jelte/cullpp) - A minimal wlroots-based region selector implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [dulcepan](https://codeberg.org/vyivel/dulcepan) - A screenshot tool for wlroots-based Wayland compositors, implementing the `wlr-layer-shell-unstable-v1` and `wlr-screencopy-unstable-v1` protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [grim](https://gitlab.freedesktop.org/emersion/grim) - Grab images from a Wayland compositor
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [shotman](https://git.sr.ht/~whynothugo/shotman) - A screenshot GUI for Wayland compositors implementing `wlr-layer-shell-unstable-v1`, `wlr-screencopy-unstable-v1`, and `single-pixel-buffer-v1` protocols
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [sneemok](https://codeberg.org/fn3x/sneemok) - A screenshot annotation tool for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Taiga](https://hg.sr.ht/~scoopta/taiga) - An animated screenshot program for wlroots-based Wayland compositors
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Wayshot](https://git.sr.ht/~shinyzenith/wayshot) - A screenshot tool for wlroots-based compositors implementing `wlr-screencopy-unstable-v1`

## SESSION MANAGEMENT

* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlogout](https://github.com/ArtsyMacaw/wlogout) ⭐ 1,049 | 🐛 45 | 🌐 C | 📅 2024-07-04 - A Wayland-based logout menu
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [wleave](https://github.com/AMNatty/wleave) ⭐ 340 | 🐛 9 | 🌐 Rust | 📅 2026-07-25 - A Wayland-based logout menu implementing the `gtk3-layer-shell` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [SwayAudioIdleInhibit](https://github.com/ErikReider/SwayAudioIdleInhibit) ⭐ 259 | 🐛 16 | 🌐 C++ | 📅 2025-11-27 - Prevents swayidle from sleeping while any application is outputting or receiving audio, implementing the `idle-inhibit-unstable-v1` protocol
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [nwg-bar](https://github.com/nwg-piotr/nwg-bar) ⭐ 175 | 🐛 6 | 🌐 Go | 📅 2024-08-30 - A Wayland-based logout menu implementing the `gtk3-layer-shell` protocol

## THEMING

* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [nwg-look](https://github.com/nwg-piotr/nwg-look) ⭐ 998 | 🐛 28 | 🌐 Go | 📅 2026-07-08 - A GTK 3 settings editor designed to work properly in a wlroots-based environment

## TOOLS

* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [lan-mouse](https://github.com/feschber/lan-mouse) ⭐ 5,143 | 🐛 128 | 🌐 Rust | 📅 2026-06-28 - A mouse and keyboard sharing software
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [ydotool](https://github.com/ReimuNotMoe/ydotool) ⭐ 2,333 | 🐛 95 | 🌐 C | 📅 2025-12-22 - A generic Linux command-line automation tool
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wayvnc](https://github.com/any1/wayvnc) ⭐ 1,797 | 🐛 43 | 🌐 C | 📅 2026-08-01 - A VNC server for wlroots-based Wayland compositors
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [hyprpicker](https://github.com/hyprwm/hyprpicker) ⭐ 1,123 | 🐛 24 | 🌐 C++ | 📅 2026-08-20 - A wlroots-compatible Wayland color picker
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wl-kbptr](https://github.com/moverest/wl-kbptr) ⭐ 733 | 🐛 42 | 🌐 C | 📅 2026-06-01 - A utility to help move the mouse pointer with the keyboard implementing the `wlr-layer-shell-unstable-v1` and `wlr-virtual-pointer-unstable-v1` protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wtype](https://github.com/atx/wtype) ⭐ 552 | 🐛 42 | 🌐 C | 📅 2024-04-27 - A Wayland tool that allows keyboard input simulation like [`xdotool`](https://github.com/jordansissel/xdotool) ⭐ 3,839 | 🐛 323 | 🌐 C | 📅 2026-06-30
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [waynergy](https://github.com/r-c-f/waynergy) ⭐ 456 | 🐛 32 | 🌐 C | 📅 2024-07-05 - An implementation of a synergy client for Wayland compositors
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [wlr-which-key](https://github.com/MaxVerevkin/wlr-which-key) ⭐ 377 | 🐛 19 | 🌐 Rust | 📅 2025-11-21 - A keymap manager for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [scenefx](https://github.com/wlrfx/scenefx) ⭐ 229 | 🐛 42 | 🌐 C | 📅 2026-08-16 - A drop-in replacement for the wlroots scene-graph API that allows Wayland compositors to render surfaces with eye-candy effects
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [waycorner](https://github.com/AndreasBackx/waycorner) ⭐ 149 | 🐛 7 | 🌐 Rust | 📅 2025-05-14 - Hot corners for wlroots-based Wayland compositors implementing the `xdg-output-unstable-v1` protocol
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [wayland-debug](https://github.com/wmww/wayland-debug) ⭐ 91 | 🐛 11 | 🌐 Python | 📅 2026-05-14 - A command-line tool for debugging Wayland clients and servers
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [whisper-overlay](https://github.com/oddlama/whisper-overlay) ⭐ 89 | 🐛 6 | 🌐 Rust | 📅 2024-07-26 - A tool providing speech-to-text functionality for Wayland compositors implementing `virtual-keyboard-unstable-v1` and `wlr-layer-shell-unstable-v1` protocols
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [wlcs](https://github.com/canonical/wlcs) ⭐ 59 | 🐛 28 | 🌐 C++ | 📅 2026-08-04 - A protocol-conformance-verifying test suite usable by Wayland compositor implementors
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Vigiland](https://github.com/Jappie3/vigiland) ⭐ 36 | 🐛 2 | 🌐 Rust | 📅 2024-06-26 - An application implementing the `idle-inhibit-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [clipcell](https://github.com/divadiahim/clipcell) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2025-06-09 - A clipboard manager with support for text and image preview for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [wlprobe](https://github.com/PolyMeilex/wlprobe) ⭐ 10 | 🐛 3 | 🌐 Rust | 📅 2026-03-02 - A utility for displaying information about the protocols supported by a Wayland compositor in a JSON format
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [wlosd](https://github.com/fshaked/wlosd) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - An on-screen display for Wayland compositors implementing the `gtk4-layer-shell` protocol
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [sway-fader](https://github.com/mgnsk/sway-fader) ⚠️ Archived - A tool that can be used to control transparency for focus and window events
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [dd99 Wayland Library](https://github.com/Delta-dev-99/dd99_wayland) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2024-06-18 - A Wayland protocol scanner
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [Meadhall](https://github.com/hkupty/meadhall) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2025-02-01 - A Wayland utilities daemon designed to centralize communication
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [wayland-display-info](https://github.com/acrion/wayland-display-info) ⭐ 1 | 🐛 0 | 🌐 C++ | 📅 2026-04-30 - A lightweight user daemon that monitors Wayland outputs via the `wlr-output-management-unstable-v1` protocol
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [wledges](https://github.com/fshaked/wledges) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - A tool for managing screen edges on wlroots-based Wayland compositors implementing the `gtk4-layer-shell` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Door Knocker](https://codeberg.org/tytan652/door-knocker) - A simple tool to check the availability of XDG portals in a running session
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [ls-wayland](https://gitlab.com/robustus/ls-wayland) - List the Wayland global environment
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [lswt](https://git.sr.ht/~leon_plickat/lswt) - List Wayland toplevels in both human readable and machine parsable formats via the `wlr-foreign-toplevel-management-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [randfall](https://gitlab.freedesktop.org/vyivel/randfall) - A collection of Wayland clients to check how a compositor handles unusual client behavior
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Waycheck](https://gitlab.freedesktop.org/serebit/waycheck) - A simple application that displays all of the Wayland protocols supported and unsupported by the running compositor
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [waydapt](https://gitlab.freedesktop.org/jonleivent/waydapt) - A Wayland compositor protocol adapter that can proxy or filter communication between a compositor and one or more clients
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [waylevel](https://git.sr.ht/~shinyzenith/waylevel) - A simple debugging tool which prints Wayland toplevels and other compositor specific information
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [waypipe](https://gitlab.freedesktop.org/mstoeckl/waypipe) - A proxy for Wayland clients enabling application forwarding similar to `ssh -X`
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [wayprompt](https://git.sr.ht/~leon_plickat/wayprompt) - A multi-purpose prompt tool for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wev](https://git.sr.ht/~sircmpwn/wev) - A tool for debugging events on a Wayland window, analogous to the X11 tool `xev`
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [windowtolayer](https://gitlab.freedesktop.org/mstoeckl/windowtolayer) - A tool that individually transforms existing Wayland clients using the `xdg-shell` protocol into clients that use `wlr-layer-shell-unstable-v1` instead to render as a wallpaper
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlopm](https://git.sr.ht/~leon_plickat/wlopm) - A Wayland output power management tool implementing the `wlr-output-power-management-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlr-board](https://gitlab.com/3443e/wlr-board) - A lightweight key overlay for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlrctl](https://git.sr.ht/~brocellous/wlrctl) - A command-line utility for miscellaneous wlroots-based Wayland extensions, supporting the `wlr-foreign-toplevel-management-unstable-v1`, `virtual-keyboard-unstable-v1`, and `wlr-virtual-pointer-unstable-v1` protocols
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [xwayland-run](https://gitlab.freedesktop.org/ofourdan/xwayland-run) - A set of utilities revolving around running `Xwayland` and various Wayland compositors headless

## WALLPAPER

* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [mpvpaper](https://github.com/GhostNaN/mpvpaper) ⭐ 1,574 | 🐛 16 | 🌐 C | 📅 2026-07-25 - A video wallpaper program for wlroots-based Wayland compositors
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Hyprpaper](https://github.com/hyprwm/hyprpaper) ⭐ 1,345 | 🐛 51 | 🌐 C++ | 📅 2026-08-13 - A wallpaper utility with the ability to dynamically change wallpapers supporting all wlroots-based compositors
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [Waypaper](https://github.com/anufrievroman/waypaper) ⭐ 1,051 | 🐛 22 | 🌐 Python | 📅 2026-06-10 - A GUI frontend for swaybg/swww to switch wallpapers
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [swaybg](https://github.com/swaywm/swaybg) ⭐ 811 | 🐛 14 | 🌐 C | 📅 2026-05-25 - A wallpaper utility for Wayland compositors implementing the `wl_output` version 4 and `wlr-layer-shell-unstable-v1` protocols
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [wpaperd](https://github.com/danyspin97/wpaperd) ⭐ 604 | 🐛 30 | 🌐 Rust | 📅 2026-08-10 - A wallpaper daemon that shows random wallpapers from a directory and changes them after some time
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [Wallutils](https://github.com/xyproto/wallutils) ⭐ 521 | 🐛 5 | 🌐 Go | 📅 2026-06-04 - A set of utilities to manage monitors, resolutions, wallpapers and timed wallpapers
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [Azote](https://github.com/nwg-piotr/azote) ⭐ 412 | 🐛 9 | 🌐 Python | 📅 2025-05-01 - A GTK 3-based picture browser and background setter supporting all wlroots-based Wayland compositors
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [neowall](https://github.com/1ay1/neowall) ⭐ 254 | 🐛 1 | 🌐 C | 📅 2026-08-11 - A shader-based GPU-accelerated wallpaper engine for Wayland compositors implementing either the `kde-plasma-shell` or `wlr-layer-shell-unstable-v1` protocols
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [yin](https://github.com/SaverinOnRails/yin) ⭐ 214 | 🐛 1 | 🌐 C++ | 📅 2026-08-01 - An efficient animated wallpaper daemon for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [rwpspread](https://github.com/0xk1f0/rwpspread) ⭐ 42 | 🐛 0 | 🌐 Rust | 📅 2026-08-18 - A multi-monitor wallpaper utility spanning input wallpapers across all monitors, supporting Wayland compositors implementing `xdg-output-unstable-v1` with integrations for `wpaperd`, `swaybg`, `hyprpaper`, `swaylock`, and `hyprlock`
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [glshell](https://github.com/Duckonaut/glshell) ⭐ 9 | 🐛 1 | 🌐 C++ | 📅 2024-01-28 - A shader display implementing the `wlr-layer-shell-unstable-v1` protocol that can be used to create a simple overlay for a Wayland compositor, a status bar, or a wallpaper
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [waul](https://github.com/hoppxi/waul) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2026-02-28 - A minimalistic wallpaper daemon for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [awww](https://codeberg.org/LGFae/awww) - An animated wallpaper daemon for Wayland, controlled at runtime and implementing the `wlr-layer-shell-unstable-v1` and `xdg-output-unstable-v1` protocols
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [beanbag](https://codeberg.org/bwbuhse/beanbag) - A lightweight wallpaper application designed for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [livebg](https://codeberg.org/mbitsnbites/livebg) - A shader-based live wallpaper application for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wawa](https://codeberg.org/sewn/wawa) - A wallpaper setter for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wbg](https://codeberg.org/dnkl/wbg) - A simple wallpaper application for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol

## WIDGETS (BARS, PANELS, ETC.)

* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Eww](https://github.com/elkowar/eww) ⭐ 12,615 | 🐛 378 | 🌐 Rust | 📅 2026-07-17 - A standalone widget system that allows for implementing custom widgets in any window manager
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Waybar](https://github.com/Alexays/Waybar) ⭐ 11,820 | 🐛 713 | 🌐 C++ | 📅 2026-08-20 - A highly customizable bar for Sway and wlroots-based compositors
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [i3status-rust](https://github.com/greshake/i3status-rust) ⭐ 3,138 | 🐛 120 | 🌐 Rust | 📅 2026-08-15 - A resource-friendly and feature-rich replacement for i3status
* ![TypeScript](https://img.shields.io/badge/typescript-%233178c6.svg?style=plastic\&logo=typescript\&logoColor=%23faf9f8) [ags](https://github.com/Aylur/ags) ⭐ 3,078 | 🐛 30 | 🌐 TypeScript | 📅 2026-04-08 - A standalone library for creating GTK-based widgets
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Ironbar](https://github.com/JakeStanger/ironbar) ⭐ 1,439 | 🐛 121 | 🌐 Rust | 📅 2026-08-19 - A customizable and feature-rich GTK bar for wlroots-based compositors
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [fabric](https://github.com/Fabric-Development/fabric) ⭐ 1,355 | 🐛 11 | 🌐 Python | 📅 2026-08-19 - A GTK-based desktop widget framework
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wob](https://github.com/francma/wob) ⭐ 1,148 | 🐛 15 | 🌐 C | 📅 2026-05-23 - A lightweight overlay volume/backlight/progress/anything bar for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) ![Vala](https://img.shields.io/badge/vala-%237b6ca3.svg?style=plastic\&logo=vala\&logoColor=fff) [Astal](https://github.com/Aylur/astal) ⭐ 976 | 🐛 93 | 🌐 Vala | 📅 2026-08-18 - A framework for creating GTK-based widgets for use with Wayland compositors
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [nwg-panel](https://github.com/nwg-piotr/nwg-panel) ⭐ 780 | 🐛 41 | 🌐 Python | 📅 2026-07-09 - A GTK 3-based panel for Wayland compositors
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [ignis](https://github.com/ignis-sh/ignis) ⭐ 679 | 🐛 66 | 🌐 Python | 📅 2026-08-18 - A widget system based on GTK 4 for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [gBar](https://github.com/scorpion-26/gBar) ⭐ 538 | 🐛 38 | 🌐 C++ | 📅 2024-12-17 - A status bar written with GTK
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [SFWBar](https://github.com/LBCrion/sfwbar) ⭐ 423 | 🐛 53 | 🌐 C | 📅 2026-08-11 - A flexible taskbar application for Wayland compositors, designed with a stacking layout in mind
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [dynisland](https://github.com/cr3eperall/dynisland) ⭐ 258 | 🐛 0 | 🌐 Rust | 📅 2025-08-01 - An extensible bar for wlroots-based Wayland compositors implementing the `gtk4-layer-shell` protocol
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [Tsumiki](https://github.com/rubiin/Tsumiki) ⭐ 234 | 🐛 2 | 🌐 Python | 📅 2026-08-19 - A Fabric-based modular status bar for Hyprland
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [syshud](https://github.com/System64fumo/syshud) ⭐ 209 | 🐛 2 | 🌐 C++ | 📅 2026-05-28 - A system status indicator for wlroots-based Wayland compositors, implementing the `gtk4-layer-shell` protocol
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [nwg-wrapper](https://github.com/nwg-piotr/nwg-wrapper) ⭐ 200 | 🐛 8 | 🌐 Python | 📅 2024-07-23 - A simple text-based wrapper that displays script or file output on the desktop of wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` and `gtk3-layer-shell` protocols
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wl\_shimeji](https://github.com/CluelessCatBurger/wl_shimeji) ⭐ 196 | 🐛 13 | 🌐 C | 📅 2026-08-13 - A widget overlay for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [way-edges](https://github.com/way-edges/way-edges) ⭐ 149 | 🐛 17 | 🌐 Rust | 📅 2026-08-16 - A lightweight application providing off-screen widgets hidden along the edges of the screen
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [sysbar](https://github.com/System64fumo/sysbar) ⭐ 97 | 🐛 0 | 🌐 C++ | 📅 2026-08-12 - A modular status bar for wlroots-based Wayland compositors, implementing the `gtk4-layer-shell` protocol
* ![Go](https://img.shields.io/badge/go-%2300add8.svg?style=plastic\&logo=go\&logoColor=fff) [YaGoStatus](https://github.com/burik666/yagostatus) ⭐ 81 | 🐛 2 | 🌐 Go | 📅 2025-02-17 - A replacement for i3status
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [creek](https://github.com/nmeum/creek) ⭐ 70 | 🐛 8 | 🌐 Zig | 📅 2026-07-22 - A dwm-inspired fork of levee and minimalist status bar for the river-classic compositor designed to be more malleable by allowing arbitrary text rather than built-in modules
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [Wapanel](https://github.com/Firstbober/wapanel) ⭐ 64 | 🐛 6 | 🌐 C++ | 📅 2022-02-13 - A simple panel/status bar/task bar for stacking Wayland-based desktops
* ![Vala](https://img.shields.io/badge/vala-%237b6ca3.svg?style=plastic\&logo=vala\&logoColor=fff) [Hybridbar](https://github.com/hcsubser/hybridbar) ⭐ 63 | 🐛 3 | 🌐 Vala | 📅 2024-09-20 - A top panel forked from wingpanel for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Dart](https://img.shields.io/badge/dart-29b6f6?style=plastic\&logo=dart\&logoColor=01579b) ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [kitshell](https://github.com/bootloopmaster636/kitshell) ⭐ 32 | 🐛 2 | 🌐 Dart | 📅 2026-04-18 - A Flutter-based panel for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C++](https://img.shields.io/badge/c++-%235e97d0.svg?style=plastic\&logo=c%2B%2B\&logoColor=fff) [zenway](https://github.com/2hdddg/zenway) ⭐ 28 | 🐛 1 | 🌐 C++ | 📅 2024-11-21 - A sway bar alternative that overlays on top of workspaces
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [ergo](https://github.com/pubfnmain/ergo) ⭐ 20 | 🐛 2 | 🌐 C | 📅 2025-12-18 - A minimal status bar for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [deburr](https://github.com/gitRaiku/deburr) ⭐ 12 | 🐛 1 | 🌐 C | 📅 2025-07-13 - A dwm-like status bar for wlroots-based Wayland compositors
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [diowpanel](https://github.com/DiogenesN/diowpanel) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2024-11-29 - A simple panel for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [walrus-bar](https://github.com/elijahimmer/walrus-bar) ⚠️ Archived - A status bar for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [diowwindowlist](https://github.com/DiogenesN/diowwindowlist) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2024-09-07 - A simple GUI application for listing and activating the currently opened toplevels (application windows) in wlroots-based Wayland compositors implementing the `wlr-foreign-toplevel-management-unstable-v1` and `wlr-layer-shell-unstable-v1` protocols
* ![Rust](https://img.shields.io/badge/rust-%23281c1c.svg?style=plastic\&logo=rust\&logoColor=fff) [Dvvidget](https://github.com/BL-CZY/dvvidget) ⭐ 3 | 🐛 1 | 🌐 Rust | 📅 2025-05-25 - A widget system for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` and `gtk4-layer-shell` protocols
* ![Python](https://img.shields.io/badge/python-4584b6?style=plastic\&logo=python\&logoColor=ffde57) [animation-speech](https://github.com/rcspam/animation-speech) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2026-03-28 - A configurable transparent speech animation overlay for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` and `gtk3-layer-shell` protocols
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [beanclock](https://codeberg.org/bwbuhse/beanclock) - A simple clock overlay for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [chocobar](https://codeberg.org/notchoc/chocobar) - A simple status bar for wlroots-based Wayland compositors
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [dam](https://codeberg.org/sewn/dam) - A small status bar designed for river-classic and wlroots-based Wayland compositors
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [labline](https://codeberg.org/ch3rn1ka/labline) - A status panel for Wayland compositors implementing the `wlr-layer-shell-unstable-v1` and `ext-workspace-v1` protocols
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [levee](https://git.sr.ht/~andreafeletto/levee) - A status bar for the river Wayland compositor, providing support for workspace tags, volume, battery capacity, and screen brightness via built-in modules
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [Root Bar](https://hg.sr.ht/~scoopta/rootbar) - A bar for wlroots-based Wayland compositors such as sway
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wayloadmon](https://git.sr.ht/~leon_plickat/wayloadmon) - A load monitor widget for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wlclock](https://git.sr.ht/~leon_plickat/wlclock) - An analog clock for wlroots-based Wayland compositors, implementing the `wlr-layer-shell-unstable-v1` protocol
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [wtw](https://codeberg.org/sewn/wtw) - A simple text widget for wlroots-based Wayland compositors implementing the `wlr-layer-shell-unstable-v1` protocol
* ![Zig](https://img.shields.io/badge/zig-%23f7a41d.svg?style=plastic\&logo=zig\&logoColor=fff) [zbar](https://codeberg.org/nwormek/zbar) - A simple status bar for dwl implementing the `wlr-layer-shell-unstable-v1` and `dwl-ipc-unstable-v2` protocols

## WINDOW MANAGERS

A number of window managers for Wayland are being developed using the [`river-window-management-v1` protocol](https://isaacfreund.com/docs/wayland/river-window-management-v1/). That list is being maintained within [River's wiki](https://codeberg.org/river/wiki/src/branch/main/pages/wm-list.md).

* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [velox](https://github.com/michaelforney/velox) ⭐ 606 | 🐛 14 | 🌐 C | 📅 2026-04-10 - A simple window manager based on swc, inspired by dwm and xmonad
* ![C](https://img.shields.io/badge/c-%23044f88.svg?style=plastic\&logo=c\&logoColor=fff) [tinybox](https://github.com/icedman/tinybox) ⭐ 31 | 🐛 3 | 🌐 C | 📅 2023-08-08 - A window manager based on tinywl inspired by Blackbox, Fluxbox, and Openbox

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-20._
