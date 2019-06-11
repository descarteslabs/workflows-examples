# Workflows Examples

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/descarteslabs/workflows-examples/master?urlpath=/lab/tree/login-notebook.ipynb)

A repository of example notebooks using the Workflows API.

Workflows offers some notebook-specific features (like interactive visualization on a map) that can't be shown easily with normal documentation. The [documentation](https://docs.descarteslabs.com/descarteslabs/workflows/readme.html) is still the place to go for API reference, high-level guides, and tutorials that don't revolve around notebook features, but this repository demonstrates what your day-to-day patterns of using Workflows in a notebook might look like.

## Running these examples in Binder

Use the [Binder](https://mybinder.org/v2/gh/descarteslabs/workflows-examples/master?urlpath=/lab/tree/login-notebook.ipynb) to launch a JupyterHub instance with the Workflows client and all dependencies pre-installed.

**Only use Python 2**. The Workflows backend is currently incompatible with Python 3 (though this will soon be fixed and Python 2 will be deprecated).

Follow the instructions to authenticate with your Descartes Labs credentials, then open any of the example notebooks and run them.

**Note:** Workflows is currently a restricted feature. Though this repository is public and you can play around with the client code, the backend will reject requests from non-whitelisted accounts.
