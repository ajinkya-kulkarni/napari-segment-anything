# napari-segment-anything

[![License Apache Software License 2.0](https://img.shields.io/pypi/l/napari-segment-anything.svg?color=green)](https://github.com/jookuma/napari-segment-anything/raw/main/LICENSE)
[![PyPI](https://img.shields.io/pypi/v/napari-segment-anything.svg?color=green)](https://pypi.org/project/napari-segment-anything)
[![Python Version](https://img.shields.io/pypi/pyversions/napari-segment-anything.svg?color=green)](https://python.org)
[![tests](https://github.com/jookuma/napari-segment-anything/workflows/tests/badge.svg)](https://github.com/jookuma/napari-segment-anything/actions)
[![codecov](https://codecov.io/gh/jookuma/napari-segment-anything/branch/main/graph/badge.svg)](https://codecov.io/gh/jookuma/napari-segment-anything)
[![napari hub](https://img.shields.io/endpoint?url=https://api.napari-hub.org/shields/napari-segment-anything)](https://napari-hub.org/plugins/napari-segment-anything)

Napari plugin of [Segment Anything Model (SAM)](https://github.com/facebookresearch/segment-anything)

Download the network weights [here](https://github.com/facebookresearch/segment-anything#model-checkpoints)

----------------------------------

This [napari] plugin was generated with [Cookiecutter] using [@napari]'s [cookiecutter-napari-plugin] template.

<!--
Don't miss the full getting started guide to set up your new package:
https://github.com/napari/cookiecutter-napari-plugin#getting-started

and review the napari docs for plugin developers:
https://napari.org/stable/plugins/index.html
-->

## Installation

You can install `napari-segment-anything` via [pip]:

```bash
pip install git+https://github.com/facebookresearch/segment-anything.git
pip install napari-segment-anything
```

To install the latest development version :

```bash
pip install git+https://github.com/facebookresearch/segment-anything.git
pip install git+https://github.com/jookuma/napari-segment-anything.git
```

## Instructions

- The first step is to load your weights into the file using the file dialog.
- The prediction is computed automatically when the annotations layers are updated.
- For points supervision, left clicks are positive cues (object) and right clicks are negative (background).

## Contributing

Contributions are very welcome. Tests can be run with [tox], please ensure
the coverage at least stays the same before you submit a pull request.

## License

Distributed under the terms of the [Apache Software License 2.0] license,
"napari-segment-anything" is free and open source software

## Issues

If you encounter any problems, please [file an issue] along with a detailed description.

[napari]: https://github.com/napari/napari
[Cookiecutter]: https://github.com/audreyr/cookiecutter
[@napari]: https://github.com/napari
[MIT]: http://opensource.org/licenses/MIT
[BSD-3]: http://opensource.org/licenses/BSD-3-Clause
[GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
[GNU LGPL v3.0]: http://www.gnu.org/licenses/lgpl-3.0.txt
[Apache Software License 2.0]: http://www.apache.org/licenses/LICENSE-2.0
[Mozilla Public License 2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
[cookiecutter-napari-plugin]: https://github.com/napari/cookiecutter-napari-plugin

[file an issue]: https://github.com/jookuma/napari-segment-anything/issues

[napari]: https://github.com/napari/napari
[tox]: https://tox.readthedocs.io/en/latest/
[pip]: https://pypi.org/project/pip/
[PyPI]: https://pypi.org/
