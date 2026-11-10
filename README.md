# Smargasy Umbrel community app store

Community app store for [OneControl](https://github.com/smargasy/rv-onecontrol) — a self-hosted web dashboard for Lippert **IdsCan** RV gateways.

## Install

1. On umbrelOS, open **App Store** → **⋯** → **Community app stores**.
2. Paste `https://github.com/smargasy/rv-onecontrol-umbrel` and add the store.
3. Open the **Smargasy** store and install **OneControl**.

## GHCR package visibility

The app image is `ghcr.io/smargasy/rv-onecontrol`. For installs to pull without extra auth, set the package to **Public** on GitHub: **Packages** → **rv-onecontrol** → **Package settings** → **Change visibility**.

## Updates

Bump the image tag in `smargasy-rv-onecontrol/docker-compose.yml`, update `version` and `releaseNotes` in `umbrel-app.yml`, and push to `main`.

## Live coach use

Only run **one** instance against the gateway at a time, and close the official OneControl mobile app first (the gateway allows a single TCP client).
