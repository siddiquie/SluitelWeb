# SluitelWeb

This repository includes the SHcms (SidHosting Content Management System) as a Git submodule.

## About SHcms

SHcms is a modular PHP-based Content Management System with a unique plugin architecture. It follows the concept: **Rules + Plugins = Suite**, and **Suite + Config = Project**.

For more details about SHcms, see the [SHcms README](SHcms/README.md).

## Getting Started

After cloning this repository, initialize and update the submodules:

```bash
git clone https://github.com/siddiquie/SluitelWeb.git
cd SluitelWeb
git submodule init
git submodule update
```

Or clone with submodules in one command:

```bash
git clone --recursive https://github.com/siddiquie/SluitelWeb.git
```

## SHcms Integration

The SHcms repository is located in the `SHcms/` directory as a Git submodule. This allows the SHcms project to be maintained separately while being integrated into SluitelWeb.

To update SHcms to the latest version:

```bash
cd SHcms
git pull origin master
cd ..
git add SHcms
git commit -m "Update SHcms submodule"
```