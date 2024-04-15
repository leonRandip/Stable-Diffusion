--Stable Diffusion in WindowsOS--

Requirements:

![Your paragraph text (3)](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/0ca38ce3-3e5b-474f-b59b-431a31ede8ce)

Step 1: Install python
You will need Python 3.10.6. (DON’T use Python 3.11 or newer) There are two ways to install Python on Windows

Option 1: Install from the Microsoft store.

Option 2: Use the 64-bit Windows installer provided by the Python website. (If you use this option, make sure to select “Add Python to 3.10 to PATH“)

I recommend installing it from the Microsoft store.

First, remove all Python versions you have previously installed. You can do that in Control Panel → Add or remove programs.

Visit Python 3.10 on Microsoft Store and install the Python software.

This step is most likely to go wrong. Let’s do a check.

Press the Windows key on your keyboard and type “cmd” to find a program called “Command Prompt”.

![image](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/cced848d-78af-474e-819c-7caf12a6d8d4)

Open the Command Prompt App. You should see a black terminal like you are a hacker…

Type “python” and press Enter. You should see you see it prints out Python 3.10. This tells you your Python is installed correctly.

Now you can close the Command Prompt App.

Don’t proceed to the next step until you get Python 3.10 installed correctly.

If you don’t see Python 3.10 running, try

-Restarting the PC
-Removing all the previous versions of Python and reinstalling from the Microsoft Store
-If the one from Microsoft Store doesn’t work for you, remove it and try the one on the Python website.

Step 2: Install git
Git is a code repository management system. You will need it to install and update AUTOMATIC1111.

Go to this page to download the windows version.

Open the installer. Click Install to accept the license and install the software.

![image](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/78abd931-bc22-4727-81c9-e42c9a1d6f33)

Step 3: Clone web-ui
This step downloads the Stable Diffusion software (AUTOMATIC1111).

Press the Window key (It should be on the left of the space bar on your keyboard), and a search window should appear. Type `cmd`.
Click on Command Prompt. The command prompt window would show up.

First, make sure you are in your home folder by typing the following command and then pressing Enter. (Tip: You should be able to use right-click to paste in Command Prompt.)

`cd %userprofile%`

You should see your prompt shows something like `C:\Users\YOUR_USER_NAME>`.

Next type the following command and press Enter to clone the AUTOMATIC1111 repository.

`git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git`

![image](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/e09205a3-09f8-4b01-9b87-9a28b9287f8b)

A folder called stable-diffusion-webui should be created in your home directory.

It’s ok to clone the repository in a different folder instead of `%userprofile%`, as long as you can find the newly created stable-diffusion-webui folder. You will need to change the folder location accordingly in the following steps.

Step 4: Download a model file

Next, go to the newly created folder in File Explorer. Put in

`%userprofile%\stable-diffusion-webui`

in the address bar and press enter.

![image](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/5297fb66-3d7a-4da7-828e-4c889bedf6db)

Navigate to the folder models and then Stable-diffusion. You should see a file Put Stable Diffusion checkpoints here.txt like below.

![image](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/e015e80a-faf3-4f5c-9ef2-dbc549c0f4ab)

Download the Stable Diffusion v1.5 model checkpoint file (download link). Put it in that folder.

Step 5: Run webui

Now in File Explorer, go back to the stable-diffusion-webui folder. That is, go back up two levels or type

`%userprofile%\stable-diffusion-webui`

again in the address bar.

Find a file called `webui-user.bat.` Double-click to run and complete the installation.

![image](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/7c5deeff-4ccb-4109-b281-6ed3111dfbc9)

This last step is going to take a while. When it is done, you will see a message

`Running on local URL: http://127.0.0.1:7860`

like the one below.

![image](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/32b945ce-ec11-424f-a868-d0c7d17c9332)

In your web browser, go to the URL

`http://127.0.0.1:7860/`

You should see the AUTOMATIC1111 webui! Put in a prompt (e.g. “a cat”) and hit Generate to test if Stable Diffusion is running correctly.

![image](https://github.com/leonRandip/Stable-Diffusion/assets/123591141/f976f239-dc3e-4f9a-9118-e99aba35ed01)

When you are done using Stable Diffusion, close the cmd black window to shut down Stable Diffusion.

To rerun Stable Diffusion, you need to double-click the `webui-user.bat.`


--Have a nice day--
