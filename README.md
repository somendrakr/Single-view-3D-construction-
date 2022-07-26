
## READ ME


## RESULTS
***Input***
 ![00_input](https://user-images.githubusercontent.com/61977952/181108226-337199f4-9416-46c6-b86a-7020ddff9fe6.jpg) 
 ***output***
 ![result_gif](https://user-images.githubusercontent.com/61977952/181108014-85c999cd-3ea8-45c4-ae9d-37a3ccc35f5e.gif)   



## Installation


create an anaconda env by running the command given below

You can create an anaconda environment called `dvr` using
```
conda env create -f environment.yaml
conda activate dvr
```


## Demo
use the command given below to run the construction. For input put the file inside the media/my_images folder.
Make sure the image have single object and with wihte background.

```
python generate.py configs/demo/demo_combined.yaml
```
This script should create a folder `out/demo/demo_combined` where the output meshes are stored.
The script will copy the inputs into the `generation/inputs` folder and creates the meshes in the `generation/meshes` folder.
the script creates a `generation/vis` folder where both inputs and outputs are copied together.

***Referance of the code ***
https://github.com/autonomousvision/differentiable_volumetric_rendering
