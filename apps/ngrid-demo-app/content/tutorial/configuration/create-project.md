---
title: Creating an Angular Project
path: tutorial/configuration/create-project
parent: tutorial/configuration
ordinal: 0
---

# Create a New Workspace and Application

We will use the Angular CLI to create a new application and workspace. This tutorial assumes you have the Angular CLI installed
globally. There are two common package managers that are supported by the Angular CLI: 
[npm](./create-project#create-an-application-with-npm) and 
[yarn](./create-project#create-an-application-with-yarn). This tutorial will support both.
If you're unsure which package manager to use, stick with the default Angular CLI configuration which uses `npm`.

## Create an Application with NPM

The Angular CLI is configured to use the NPM package manager by default. To create a new app, run this command in a terminal:

```bash
ng new ngrid-tutorial
```

W> The `ng new` command is interactive. You will be asked if you would like to use **Angular routing**. Answer **yes**.
W> The CLI will prompt you to select a **stylesheet format**. Choose **SCSS**.

This command will take a while to finish, but we'll be ready to roll once it's complete. The rest of this tutorial assumes
you're in the project's root directory, so let's change into that directory now.

```bash
cd ngrid-tutorial
```
[Now let's install n**Grid**!](../install#installing-ngrid)

## Create an Application with Yarn

You can opt to use `yarn` in lieu of `npm`. This requires some additional configuration. We'll focus on how to configure
the local project to use `yarn`, but the same commands can be applied to your global Angular CLI installation.

We'll create a new application using the Angular CLI, but we're going to pass in an optional parameter. By using the `--skip-install`
option with the `ng new` CLI command, we are telling the CLI to hold off on creating a `node_modules` directory with our dependencies.
This will give us a chance to configure our project to use `yarn` before installing the necessary packages.

```bash
ng new ngrid-tutorial --skip-install
```

W> The `ng new` command is interactive. You will be asked if you would like to use **Angular routing**. Answer **yes**.
W> The CLI will prompt you to select a **stylesheet format**. Choose **SCSS**.

Next, we'll change the terminal directory into the project's root. The rest of the tutorial will assume we're in the root directory.

```bash
cd ngrid-tutorial
```

Since we've decided to use `yarn`, we need to inform the Angular CLI of our decision. Running the following command will update the `angular.json` file to reflect our choice.

```bash
ng config cli.packageManager yarn --global=false
```

Now we'll use `yarn` to install our dependencies. This command will take a while to finish, but when it's done, we're ready to begin developing:

```bash
yarn
````
[Now let's install n**Grid**!](../install#installing-ngrid)
