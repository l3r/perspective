# Perspective JupyterLab Extension
This extension allows in-lining perspective based charts in jupyterlab notebooks.

## Installation
### From npm
```bash
jupyter labextension install @jpmorganchase/perspective-jupyterlab
```

### From source
From inside the jlab directory:
```bash
npm install
npm start
jupyter labextension install .
```

### Post install
Copy `node_modules/@jpmorganchase/perspective/build/{asmjs, wasm_async, wasm_sync}` to the jupyterlab build folder (`static` inside of one of the app_dir given from the `jupyter labextension list` command)