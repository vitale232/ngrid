---
title: Installing NGrid
path: tutorial/configuration/install
parent: tutorial/configuration
ordinal: 1
---
# Installing nGrid

n**Grid** must be installed using `npm` or `yarn`. All of n**Grid** is served from the `@pebula` namespace.

When you install the core of n**Grid**, you'll get the main building blocks and core features of the grid. The main install
will also include some of the packages required to extend the functionality of n**Grid** (e.g. Target Events, Clipboard, etc.).
Additionally, there is a UI extension that builds on top of Angular Material. This extension is optional, but it's recommended 
if you're using Angular Material in your application. We'll be using Angular Material and n**Grid** Material in this tutorial.

## Installing n**Grid** and n**Grid** Material with NPM

The following command will install n**Grid** and its dependencies, including Material Design components, using `npm`:

```bash
npm install @pebula/utils @pebula/ngrid @pebula/ngrid-material
```

[Let's start building!](../../application/serve#the-application-shell)

## Installing n**Grid** and n**Grid** Material with Yarn

The following command will install n**Grid** and its dependencies, including Material Design components, using `yarn`:

```bash
yarn add @pebula/utils @pebula/ngrid @pebula/ngrid-material
```

[Let's start building!](../../application/serve#the-application-shell)
