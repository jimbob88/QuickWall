<h1 align="center">QuickWall</h1>

<div align="center" style="padding-top: 2em; padding-bottom: 2em;">
    <img src="qw.gif">
</div>

1. [Philosophy](#philosophy)
2. [How It Works](#how-it-works)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Acknowledgements](#acknowledgements)

## Philosophy

### Set latest wallpaper from Unsplash directly from the commandline.

## How It Works

### It uses [Unsplash](https://unsplash.com) API to get wallpapers and set them using nitrogen.

## Requirements

1. Python 3.4+
2. [nitrogen](https://github.com/l3ib/nitrogen)

> **NOTE**: These dependencies in linux can be installed in other variants.  
> For *arch linux*, you can use **pacman** package manager accordingly.

## Installation

* Run the following command in the root directory to install QuickWall.

```sh
python setup.py install
```

> **NOTE**: If you get **permission denied** error, run the above command with sudo.

## Acknowledgements

### [Unsplash](unsplash.com) for their awesome API.