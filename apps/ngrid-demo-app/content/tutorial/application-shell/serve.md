---
title: Serving the Application
path: tutorial/application/serve
parent: tutorial/application
ordinal: 0
---
# The Application Shell

The Angular CLI has create an application shell for us when we ran the `ng new` command in the previous step. We now have:
- A new workspace, with a root folder named `ngrid-tutorial`
- An end to end test project (in the `e2e` folder)
- Related configuration files

The initial app project contains a default welcome application that is ready to be served right away.

## Serve the Application

To serve the application, you must be in the root directory of the project. If you did not change into the root directory
earlier, we'll do so now then serve the app:

```bash
cd ngrid-tutorial
ng serve --open
```

I> The `ng serve` command will build the app, start the dev server, watch the source files, and update as changes are made.
I> <br> The `--open` flag opens a browser to `http://localhost:4200`, which is the default port for the dev server.

You should now see the app running in your browser.
