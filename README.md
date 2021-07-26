# Photo-Realistic Image Super-Resolution via Variational Autoencoders
We propose to perform Image Super-Resolution via Variational AutoEncoders (SR-VAE) learning according to the conditional distribution of the high-resolution images induced by the low-resolution images.. We claim the following points:

• Conditional sampling mechanism.

• Back projection based SR-VAE network.

• Modified VGG feature based loss estimation.

Please cite our work if you use our code or dataset as,
# BibTex

        @InProceedings{Liu2021refvae,
            author = {Zhi-Song Liu, Wan-Chi Siu and Yui-Lam Chan},
            title = {Photo-Realistic Image Super-Resolution via Variational Autoencoders},
            booktitle = {IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)},
            volume = {31},
            no = {4},
            page = {1351-1365},
            month = {April},
            year = {2021}
        }
        
# Dependencies
    Python 2.XXX<3.0
    OpenCV 3.4.0
    Caffe 
    NVIDIA GPU + CUDA
    Jupyter Notebook

# Complete Architecture
The complete architecture is shown as follows,

![network](/figures/network.PNG)

# Reimplementation
1. Download pre-trained model from the following link
---------------------------------------
    https://drive.google.com/drive/folders/1XIsjovqYszI9RvTa0RbyHQcEraZGTpfo?usp=sharing

2. Testing on 4x SR
---------------------------
    run SR_VAE_4x.ipynb

3. Testing on 8x SR
----------------------------------------------------------------------------
    run SR_VAE_8x.ipynb

# Experimental results
1. We compared our proposed approach with state-of-the-arts face image SR approaches on objective quality by using PSNR, SSIM and PI scores as follow

![Table Comparison](/figures/table.PNG)

2. We also compared different approaches on 4x SR.

![Similarity Comparison](/figures/4xsr.PNG)

3. We also compared different approaches on 8x SR.

![Visual Comparison](/figures/8xsr.PNG)
