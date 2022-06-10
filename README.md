# tauri-app
This app is a task list desktop application using the Rust framework TAURI.  
The front end uses the JavaScript framework Svelte.

## Preparation

- Rust
- Node.JS

### Windows
- Micsrosoft Visual Studio C++ build tools
- WebView2

### Linux
- Base
- build essential (Ubuntu)
- development tools (CentOS)

## Get started

Install the dependencies...

```bash
git clone https://github.com/interceptor128/tauri-app.git
cd tauri-app
yarn install
```

...then start [Rollup](https://rollupjs.org):

```bash
yarn tauri dev
```

Navigate to [localhost:8080](http://localhost:8080). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

By default, the server will only respond to requests from localhost. To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode). If you are using other editors you may need to install a plugin in order to get syntax highlighting and intellisense.

## Building and running in production mode

To create an optimised version of the app:

```bash
yarn tauri build
```
