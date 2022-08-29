# Stable-Diffusion-Helper-Scripts
### How to Use

* Clone the repo or download the files
* Copy `txt2img2.py` and `img2img2.py` to your `stable-diffusion/scripts` folder
* Run `cat ./zshrc_scripts >> ~/.zshrc`
* Open `~/.zshrc` in a text editor and fill out the `User Entered Variables` section
  * The paths for Stable Diffusion and the font to use for grid labels need to be changed for your system
  * You will need to create the prompt txt files if they do not exist
* Restart your shell or run `source ~/.zshrc`

Now you can create a list of prompts in your img or txt prompt file (1 prompt per line like with the standard script).

When you’re ready to generate, run `btxt2img` or `bimg2img /path/to/img`.

The samples (and original file for `bimg2img`) will be saved to its own timestamped directory in the output folder. The new grid will be saved to the same directory as `fullgrid.png` 

For help changing parameters, check the `~/.zshrc` file or run either command with the `--help` argument.

![](https://reticulated.net/dailyai/stable-diffusion-better-grids-and-bulk-scripts/img/image-20220828170357128.png#center)

See more examples here: https://reticulated.net/dailyai/stable-diffusion-better-grids-and-bulk-scripts/
