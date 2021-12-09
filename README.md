# Library


----

## Ubuntu Commands


#### Add PPA Public Key

`sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 40976EAF437D05B5`

> Notes
>  - Add each public key only once
>  - Ref: https://chrisjean.com/fix-apt-get-update-the-following-signatures-couldnt-be-verified-because-the-public-key-is-not-available/



----


## Pytorch


#### Install facebookresearch/fairmotion

`conda create -n fairmotion python=3.6`

`conda activate fairmotion`

`pip install torch===1.4.0 torchvision===0.5.0 -f https://download.pytorch.org/whl/torch_stable.html`

`pip install fairmotion`

