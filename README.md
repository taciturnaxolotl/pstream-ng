# pstream-ng

A fork of [P-Stream](https://github.com/p-stream/p-stream), a media streaming frontend that was [shut down under pressure from ACE/MPA](https://torrentfreak.com/pirate-streaming-portal-p-stream-shuts-down-following-ace-mpa-pressure/). This fork preserves the open-source codebase with merged community contributions and dependency updates.

> [!WARNING]
> **This software does not host, index, or distribute any copyrighted content.** It is a frontend application that interacts with user-configured backends. How it is used is entirely the responsibility of the end user.

The canonical repo for this is hosted on tangled over at [`dunkirk.sh/pstream-ng`](https://tangled.org/dunkirk.sh/pstream-ng)

## Running Locally

```bash
git clone git@knot.dunkirk.sh:dunkirk.sh/pstream-ng
cd pstream-ng
pnpm install
pnpm run dev
```

Then visit [localhost:5173](http://localhost:5173).

## Upstream

To pull in updates from the original P-Stream repo:

```bash
git fetch upstream
git merge upstream/production
```

<p align="center">
    <img src="https://raw.githubusercontent.com/taciturnaxolotl/carriage/main/.github/images/line-break.svg" />
</p>

<p align="center">
    <a href="https://github.com/p-stream/p-stream">
        <img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=Fork+of&message=P-Stream&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/>
    </a>
</p>
