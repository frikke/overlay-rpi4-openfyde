# overlay-rpi4-openfyde

![Logo badge](https://img.shields.io/badge/openFyde-Pre--built%20image%20available-success?style=flat&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAIIAAAAoCAYAAAFFgxLjAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAyhpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDcuMi1jMDAwIDc5LjU2NmViYzViNCwgMjAyMi8wNS8wOS0wODoyNTo1NSAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0UmVmPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VSZWYjIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtcE1NOkRvY3VtZW50SUQ9InhtcC5kaWQ6MDNDQzZCODhGRTc1MTFFQ0IzQ0FEMjJGQzc0NTRCQzAiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6MDNDQzZCODdGRTc1MTFFQ0IzQ0FEMjJGQzc0NTRCQzAiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIDIzLjQgKE1hY2ludG9zaCkiPiA8eG1wTU06RGVyaXZlZEZyb20gc3RSZWY6aW5zdGFuY2VJRD0ieG1wLmlpZDowM0NDNkI4M0ZFNzUxMUVDQjNDQUQyMkZDNzQ1NEJDMCIgc3RSZWY6ZG9jdW1lbnRJRD0ieG1wLmRpZDowM0NDNkI4NEZFNzUxMUVDQjNDQUQyMkZDNzQ1NEJDMCIvPiA8L3JkZjpEZXNjcmlwdGlvbj4gPC9yZGY6UkRGPiA8L3g6eG1wbWV0YT4gPD94cGFja2V0IGVuZD0iciI/PpEvYA0AAAx8SURBVHja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&logoWidth=40&labelColor=ffffff&label=) ![Release badge](https://img.shields.io/github/v/release/openFyde/overlay-rpi4-openfyde?label=latest%20release%20image)


<br>

## Introduction
Same as Chromium OS, openFyde adopts the [Portage build and packaging system](https://wiki.gentoo.org/wiki/Portage) from Gentoo Linux. openFyde uses Portage with certain customisations to support building multiple targets (bootable OS system images) across different hardware architectures from a shared set of sources.

A **board** defines a target type, it can be either for a family of hardware devices or specifically for one type of device. For example, The board `amd64-openfyde` is a target type for an openFyde system image that aims to run on most recent PCs with amd64(x86_64) architecture; whilst the `rpi4-openfyde` board is a target type specifically for the infamous single-board computer [Raspberry Pi 4B](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/). We append  Each board has a corresponding **overlay** that defines the configuration for it. This includes details like CPU architecture, kernel configuration, as well as additional packages and USE flags.

<br>

## About this repository
This repository is the overlay for the `rpi4-openfyde` board, it's part of the openFyde open-source project.

This repository contains the following packages:


| Packages                               | Description                                           | Reference                                                                                                                                      |
|----------------------------------------|-------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------|
| chromeos-base/device-appid             | Setup device appid                                    |                                                                                                                                                |
| chromeos-base/chromeos-chrome          | Open-source version of Google Chrome web browser      | [chromiumos-overlay](https://chromium.googlesource.com/chromiumos/overlays/chromiumos-overlay/+/refs/heads/main/chromeos-base/chromeos-chrome) |
| chromeos-base/chromeos-init            | Upstart init scripts for Chromium OS                  | [chromiumos-overlay](https://chromium.googlesource.com/chromiumos/overlays/chromiumos-overlay/+/refs/heads/main/chromeos-base/chromeos-init)   |
| chromeos-base/chromeos-bsp-rpi4-openfyde | drivers, config files for Raspberry Pi 4              |                                                                                                                                                |
| virtual/chromeos-bsp                   | Generic ebuild which satisifies virtual/chromeos-bsp. | [chromiumos-overlay](https://chromium.googlesource.com/chromiumos/overlays/chromiumos-overlay/+/refs/heads/main/virtual/chromeos-bsp)          |
| virtual/chromeos-config-bsp            | Chrome OS BSP config virtual package                  |                                                                                                                                                |



<br>


## About the board `amd64-openfyde`
This board targets specifically for: 

- [Raspberry Pi 4 Model B](https://www.raspberrypi.com/products/raspberry-pi-4-model-b/):

    ![Raspberry Pi 4B](https://fydeos.io/content/wp-content/uploads/2022/07/openfyde-pi4.png)

- it is also compatible with [Raspbery Pi 400](https://www.raspberrypi.com/products/raspberry-pi-400/):
    
    ![Raspberry Pi 400](https://fydeos.io/content/wp-content/uploads/2022/07/openfyde-pi400.png)


 `rpi4-openfyde` is the foundation for [FydeOS for You - Raspberry Pi 400](https://fydeos.io/download/device/rpi4-fydeos) release.

<br>

###### Copyright (c) 2022 Fyde Innovations and the openFyde Authors. Distributed under the license specified in the root directory of this repository.
