# jupyterlab_miami_nights
Combination of VS Code's SynthWave '84 and JupyterLab's Neon Night, with the glowing of "Neon Dreams" enabled
<img src="https://raw.githubusercontent.com/timkpaine/jupyterlab_miami_nights/master/screenshots/Miami Nights.png" />

original readme below


---

# Jupyterlab Neon Theme

A flat, 80's neon inspired theme for JupyterLab.

<img src="https://raw.githubusercontent.com/yeebc/jupyterlab-neon-theme/master/screenshots/Neon Night.png" />
<img src="https://raw.githubusercontent.com/yeebc/jupyterlab-neon-theme/master/screenshots/Neon Sunset.png" />

This theme is hightly inspired by artworks of 80's Neon, Synthwave and Cyberpunk. It is optimized for **long-term use** but colorful and cooool.


## Bonuses
1. Search tool + neon billboard
2. Collapser + neon light
3. Scrollbar + FM-84's "Atlas"  (compatible with webKit browsers)
4. A surprise in the presentation mode (**Top menu** --> **View** --> **Presention mode**)


## Customize
You may don't like the default background or the transparent UI, so codes concerning these controversial designs are separately put into [`custom.css`](https://github.com/yeebc/jupyterlab-neon-theme/tree/master/style/custom.css) and detailly commented for you to customize. 

After you edited css files, please follow instructions in the [Development installation](https://github.com/yeebc/jupyterlab-neon-theme#development-installation) to reinstall.

### 1. Transparent left/top bar
PLease follow the comments to ajust the transparency.

### 2. Background
Two gradient backgrounds, 'Neon Night' and 'Neon Sunset', are provided. The default style is 'Neon Night' and you can uncomment codes to employ 'Neon Sunset' style.

To use an image as background, uncomment the corresponding part of codes, and change the url to the path of your image.

### 3. Fonts
To change fonts of editor and neon, firstly, add your font files to [`fonts`](https://github.com/yeebc/jupyterlab-neon-theme/tree/master/style/fonts) directory and update [`fonts.css`](https://github.com/yeebc/jupyterlab-neon-theme/blob/master/style/fonts.css) to register them. Then follow my comments to employ your registered fonts.


## Compatibility
To support gradient scrollbars showed in screenshots, **webKit browsers** like chrome are required. Otherwise, please activate the **Theme Scrollbars** in the **Top menu** --> **Settings** --> **JupyterLab Theme** for dark scrollbars (except **Edge**). This color scheme is primarily designed for python and ipynb, so there may be issues in other situations. If any problem you find, please report it to me in the [Github](https://github.com/yeebc/jupyterlab-neon-theme/issues) and I'll try to fix it as soon as possible.


## Prerequisites
* JupyterLab >= 2.0.0

This theme is an extension of Jupyterlab. In order to install JupyterLab extensions, you need to have Node.js installed and enable the **Extension Manager** which is disabled by default. More information can be found in the [Official User Guide](https://jupyterlab.readthedocs.io/en/stable/user/extensions.html).
```bash
conda install -c conda-forge nodejs
```

## Package installation
* Using GUI

You can use the extension manager to find and install this theme for JupyterLab. Please check [Official User Guide](https://jupyterlab.readthedocs.io/en/stable/user/extensions.html#finding-extensions) for detailed instructions.

* Using the command
```bash
jupyter labextension install @yeebc/jupyterlab_neon_theme
```


## Development installation
For a development install (requires npm version 4 or later), clone this github repo and do the following in the repository directory:

```bash
npm install
jupyter labextension link .
```

To rebuild the package and the JupyterLab app:

```bash
npm run build
jupyter lab build
```


## Contributing
I welcome any contribution to this theme. You can get more imfomation about the project structure of JupyterLab theme extensions from [Official Document](https://jupyterlab.readthedocs.io/en/stable/developer/css.html).


## Thanks
You may also like  [SynthWave '84](https://github.com/robb0wen/synthwave-vscode), my favorite VS Code theme,  with similar style and  it is more compatible with HTML & CSS, JS.
