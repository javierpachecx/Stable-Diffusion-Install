# Stable Diffusion Local Installation
### Simple guide - [github.com/javierpachecx](https://github.com/javierpachecx)
###### Stable guide for Windows 10 (64bit)
---
## Installers
1. Install <a href="https://www.python.org/ftp/python/3.10.6/python-3.10.6-amd64.exe" target=_blank>Python 3.10.6</a>
    - Check "**Add Python 3.10 to PATH**"
    - Use "**Install Now**" option.
2. Install <a href="https://github.com/git-for-windows/git/releases/download/v2.39.0.windows.2/Git-2.39.0.2-64-bit.exe">Git</a>
    - "**C:\Program Files\Git**"
    - Uncheck "**Windows Explorer integration**"
    - *Continue with "Next" until the end.*
    - Uncheck "**View Release Notes**"
3. Install <a href="https://www.7-zip.org/a/7z2201-x64.exe" target=_blank>7zip</a>
    - Click on "**Install**"
---
## Base programme
4. Download "<a href="https://github.com/AUTOMATIC1111/stable-diffusion-webui/archive/refs/heads/master.zip" target=_blank>AUTOMATIC1111/stable-diffusion-webui</a>"
    - Unzip the file downloaded
        - Right click > *7zip* > **Extract here"**
5. Download "<a href="https://github.com/TencentARC/GFPGAN/releases/download/v1.3.0/GFPGANv1.4.pth" target=_blank>TencentARC/GFPGAN</a>"
6. Move "**GFPGANv1.4.pth**" to "**stable-diffusion-webui-master**" root folder.
---
## Models
7. Download model/s at your choice. Some good examples are:
    - <a href="https://huggingface.co/stabilityai/stable-diffusion-2-1/resolve/main/v2-1_768-ema-pruned.ckpt" target=_blank>stabilityai/stable-diffusion-2-1</a>
    - <a href="https://huggingface.co/runwayml/stable-diffusion-v1-5/resolve/main/v1-5-pruned-emaonly.ckpt" target=_blank>runwayml/stable-diffusion-v1-5</a>
    - <a href="https://huggingface.co/runwayml/stable-diffusion-inpainting/resolve/main/sd-v1-5-inpainting.ckpt" target=_blank>runwayml/stable-diffusion-inpainting</a>
    - Among others..
    ###### You can install as many models as you want but they are heavy *(GB)*. Within the Stable Diffusion interface you can choose the model you want to use *(top left)*.
8. Move model/s *("**.ckpt**" file)* to "**stable-diffusion-webui-master/models/Stable-diffusion/**" folder.
---
## Run
9. Open "**stable-diffusion-webui-master**" folder
10. Search "**webui-user.bat**" file
    - Right click it > **Open**
- **(!) WAIT, DO NOT CLOSE TERMINAL**
###### A few minutes later. The terminal should display the IP **127.0.0.1:7860**
11. Open your web browser and write:
    - <a href="http://127.0.0.1:7860" target=_blank>**127.0.0.1:7860**</a>
---
#### Finished, Stable Diffusion installed on your machine without the need for external hardware.
- If you want to install new models, add them to the "**models**" folder.
- If you want to close the program, **close the terminal**.
- If you want to organise your images, it will be in the folder "**outputs**".