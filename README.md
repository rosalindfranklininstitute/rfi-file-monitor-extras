# rfi-file-monitor-extras
Extra Plugins that can be built with the file monitor but are not part of the core functionality

# Installation

Create a conda environment:

```
conda create env -n rfi-file-monitor
```

Activate the environment
```angular2html
conda activate rfi-file-monitor
```
Install the rfi-file-monitor core package into this environment
```angular2html
conda install -c conda-forge rfi-file-monitor
```

Clone the `rfi-file-monitor-extras`. From inside the `rfi-file-monitor-extras` directory `pip install` the package
into the `rfi-file-monitor` conda environment:

```angular2html
pip install -e .
```