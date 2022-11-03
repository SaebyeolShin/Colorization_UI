# Colorization_UI

## Pretrained Models

Checkpoints for iColoriT models are available in the links below.

put pretrained models into  `./saved_models/best/`

|  	| hint |  Link 	|
|:---:|:---:|:---:|
| Our Model | &cross;	| [Google Drive](https://drive.google.com/file/d/1o0DbtsVW_YIpPH0rIVFLHnuBGdcdm_rV/view?usp=share_link) | 
| iColoriT | &check;	| [Google Drive](https://drive.google.com/file/d/16i9ulB4VRbFLbLlAa7UjIQR6J334BeKW/view?usp=sharing)	|

## Installation

Our code is implemented in Python 3.8, torch>=1.8.2, and PyQt5
```
git clone https://github.com/SaebyeolShin/Colorization_UI.git
pip install -r requirements.txt
```

## Run UI
Once you have satisfied all the requirements, you can run the base iColoriT model by executing

```
python3 colorize_ui.py
```

### Controls

<ul>

<li> Left click on Drawing Pad to select the hint location. 

<li> Left click on the ab Color Gamut to select a color.

<li> Right click on a hint location to undo the click.

<li> Press <em>Restart</em> to undo all hints. 

<li> Press <em>Save</em> to save the colorized image. 

<li> Press <em>Load</em> to load another image.

</ul>

## Acknowledgments

Our GUI is an updated version of the [iColoriT: Towards Propagating Local Hint to the Right Region in Interactive Colorization by Leveraging Vision Transformer](https://github.com/pmh9960/iColoriT).
Thanks for sharing the codes!
