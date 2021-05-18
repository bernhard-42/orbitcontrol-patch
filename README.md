orbitcontrol-patch
==================

A patch for pythreejs Orbitcontrol to update at init

Installation
------------

To install use pip:

    $ pip install orbitcontrol_patch

For a development installation (requires [Node.js](https://nodejs.org) and [Yarn version 1](https://classic.yarnpkg.com/)),

    $ git clone https://github.com/bernhard-42/orbitcontrol-patch.git
    $ cd orbitcontrol-patch
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --overwrite --sys-prefix orbitcontrol_patch
    $ jupyter nbextension enable --py --sys-prefix orbitcontrol_patch

When actively developing your extension for JupyterLab, run the command:

    $ jupyter labextension develop --overwrite orbitcontrol_patch

Then you need to rebuild the JS when you make a code change:

    $ cd js
    $ yarn run build

You then need to refresh the JupyterLab page when your javascript changes.
