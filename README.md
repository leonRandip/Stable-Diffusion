- [Windows](Windows.md)
# Stable-Diffusion
Install Stable Diffusion on Mac — Beginners Guide

Today, I’ll guide you through the process of installing the stable diffusion UI on your Mac so that you can generate AI images with ease. So without further delay, let’s get that stable diffusion tool fired up on your Mac!

Requirements:

You should have an Apple Silicon M1 or M2, with at least 8GB RAM. Your MacOS version should be at least 12.3.

![Your paragraph text (1)](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/8f41329a-5495-4316-9a4a-bcce214811d6)

Step-by-Step instructions

Step 1: Install Homebrew

First, we need to install Homebrew. Copy the following code:

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Open the terminal on your Mac and run the command.

Step 2: Install Required Packages

We need to install some more packages for this to work. Next, run the following command in terminal:

`brew install cmake protobuf rust python@3.10 git wget`

Step 3: Install Stable Diffusion UI

Now, we’ll install the stable diffusion UI. Type and execute the following command on terminal:

`git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui`

Step 4: Add Model Files

Once the installation is complete, open the stable diffusion web UI folder

To open the folder just run open . command on terminal, you will find stable-diffusion-webui folder there, find the ‘models’ folder in it, in models folder look for ‘Stable-diffusion’ folder and open it.

You’ll have to paste the CKPT or safetensor files for whichever model you choose to run on the stable diffusion UI.

Visit the [Hugging Face]( https://huggingface.co/ ) website to download any .ckpt file from a good model. I’m using the Protogen-Infinity (8gb), but you can choose any model of your choice. Download the .ckpt file and place it in the “stable-diffusion-webui > models > Stable-diffusion” folder.

— You can also use [Mo-di-diffusion](https://huggingface.co/nitrosocke/mo-di-diffusion) model if you don’t have enough storage on your mac, size of this ckpt file is just 2.13 gb.

- I have downloaded the [runwayml/stable-diffusion-v1-5](https://huggingface.co/runwayml/stable-diffusion-v1-5/blob/main/v1-5-pruned-emaonly.ckpt) which is an okayish model i would suggest using any other model.

Step 5: Launch the Web UI

In the terminal, type `cd stable-diffusion-webui` and then execute `./webui.sh`.

Step 6: Start Generating AI Images

<img width="571" alt="terminal.jpg" src="https://github.com/leonRandip/Stable-Diffusion/assets/123591141/44f38be2-9185-4d3f-b0d0-c5255f332474">

Copy the URL displayed in the terminal and paste it into the browser and enter your first text prompt. Voila! Stable diffusion UI is installed on your Mac, and you can start generating AI images.

-OUTPUT-

<img width="1510" alt="Output.jpg" src="https://github.com/leonRandip/Stable-Diffusion/assets/123591141/79bea794-c2a4-41b5-beb0-6031fed41bcd">

Generated Image:

![](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/14c9f303-edd3-4b0a-a4df-199879b8fe29)


--Have a nice day!--
