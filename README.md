
# ipydagred3

ipywidgets library for drawing directed acyclic graphs in jupyterlab using [dagre-d3](https://github.com/dagrejs/dagre-d3)

[![Build Status](https://dev.azure.com/tpaine154/jupyter/_apis/build/status/timkpaine.ipydagred3?branchName=main)](https://dev.azure.com/tpaine154/jupyter/_build/latest?definitionId=22&branchName=main)
[![Coverage](https://img.shields.io/azure-devops/coverage/tpaine154/jupyter/22/main)](https://dev.azure.com/tpaine154/jupyter/_build?definitionId=22&_a=summary)
[![PyPI](https://img.shields.io/pypi/l/ipydagred3.svg)](https://pypi.python.org/pypi/ipydagred3)
[![PyPI](https://img.shields.io/pypi/v/ipydagred3.svg)](https://pypi.python.org/pypi/ipydagred3)
[![npm](https://img.shields.io/npm/v/ipydagred3.svg)](https://www.npmjs.com/package/ipydagred3)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/timkpaine/ipydagred3/main?urlpath=lab)


![](https://raw.githubusercontent.com/timkpaine/ipydagred3/main/docs/img/example.gif)

## Installation

You can install using `pip`:

```bash
pip install ipydagred3
```

Or if you use jupyterlab:

```bash
pip install ipydagred3
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

If you are using Jupyter Notebook 5.2 or earlier, you may also need to enable
the nbextension:
```bash
jupyter nbextension enable --py [--sys-prefix|--user|--system] ipydagred3
```

## Features
- Dynamically create and modify graphs from python
- Change color, shape, tooltip, etc
- Click events (click on node or edge and get event in ipywidget indicating source, good for node inspector tools)


### Tooltips and Click events
![](https://raw.githubusercontent.com/timkpaine/ipydagred3/main/docs/img/example2.gif)

## Examples
Network example from the first gif
[Network Example](https://github.com/timkpaine/ipydagred3/tree/main/docs/examples/example.ipynb)

Tooltip Example from the second gif
[Tooltip Example](https://github.com/timkpaine/ipydagred3/tree/main/docs/examples/example.ipynb)
