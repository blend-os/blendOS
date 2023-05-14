<div align="center">
  <img src="https://user-images.githubusercontent.com/26926757/235855282-34d9a8f5-f92b-4ce3-855e-9e2e6551a3bf.png" alt="logo" width="200"/>

  <h1>Welcome to blendOS!</h1>
  <i>The only operating system you'll ever need. A seamless blend of all Linux distributions, Android apps and web apps.</i>
</div>

This repository acts as the starting point for contributing to blendOS.

## Contributing

There are a number of ways in which you can contribute to blendOS. All of blendOS's code is licensed under the GPL-3.0 license.

Do join the blendOS Discord server, where you'll find over 750 people ready to assist you with your contributions: https://discord.gg/m9JPmZB8Kd

### Docs

The docs are hosted at docs.blendos.co, but are pretty much empty at the moment, and thus haven't been publicly announced on the blendos.co website.

You can get started with contributing to the docs by creating a pull request at https://github.com/blend-os/docs, which uses GitHub Pages and Docusaurus.

### `blend` and `akshara`

`blend` and `akshara` are the primary components of blendOS, that handle immutability, updates, overlays and containers. Both of them are written in Python.

The `blend` repository also contains 'blendOS Settings', a GUI configuration tool for blendOS that uses Electron.

### Infrastructure

Quoting our announcement on the blendOS Discord Server.

> **rs2009#6116** | May 14, 2023 at 21:40 (IST)
>
> We're ready with a huge update to blendOS. However, it has increased requirements for infrastructure, due to the development of a new, innovative update system.
>
> We currently host our ISOs on SourceForge and Google Drive, but that would not be possible for the next release due to technical reasons. We do have the necessary infrastructure for building ISOs, but do not have the capacity to host them ourselves at the moment.
>
> We would greatly appreciate it if you have a spare VPS (or an old computer collecting dust) lying around that you could provide for hosting ISOs, with sufficient bandwidth. We plan for the build server to automatically upload generated ISOs to such servers, depending on the availability of free space as well as bandwidth constraints.
>
> This is really essential for any future releases, hence the ping.
>
> Feel free to post information about any available hardware/VPSs for hosting ISOs in the ⁠#infrastructure channel, as well as any provider suggestions that offer servers for this purpose at reasonable rates, since I'll be funding it from my pocket.
