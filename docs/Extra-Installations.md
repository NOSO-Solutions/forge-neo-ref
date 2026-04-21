> *If you don't understand, just go ask a LLM or something...*

<br>

## Github Desktop

> `Github Desktop` provides a simple **G**raphical **U**ser **I**nterface to easily clone / update / downgrade / switch branch for `git` repositories

- Download and Install from the [Official Site](https://desktop.github.com/download/)

<p align="center">
<img width=512 src="./assets/tutorials/desktop.png">
</p>

- The UI will show the modified files and their differences; non-developers can just ignore them

#### Add

- If you already cloned a repository, go to `File/Add local repository...`, and give it the path to the folder
- You can click on `Current repository` to change the repository to manage

#### Clone

- To clone *(**i.e.** download)* a new repository, go to `File/Clone repository...`, select the **URL** option, and give it the URL to the repository
- You can click on `Current repository` to change the repository to manage

#### Update

- To update the current repository, click on `Fetch origin` first. If a new commit is available, the button will become `Pull origin`. Click again to update to the latest commit.

#### Downgrade

- If an update breaks a feature, click on `History`, find the last working commit, right click, then `Checkout commit`
- To receive updates again, click on `Current branch`, and select the original branch again

#### Switch

- When there is a development branch, click on `Fetch origin` first, then click on the `Current branch` to see the list of all Branches. Simply click on the branch of choice to participate in the testing.

> [!Tip]
> If you modified the `webui-user.bat`, remember to select the **Bring my changes** option

> [!Warning]
> Do not switch between **classic** and **neo** branch

<br>
<br>

## Insightface

- https://github.com/Gourieff/Assets/tree/main/Insightface

## Sage Attention

- **Windows:**
    - https://github.com/woct0rdho/SageAttention/releases

- **Linux:**

```bash
cd sd-webui-forge-neo
source venv/bin/activate
cd ..
git clone https://github.com/thu-ml/sageattention
cd SageAttention
python setup.py install
```

## Triton

- **Windows:**

```bash
pip install triton-windows
```

- **Linux:**

```bash
pip install triton
```

## Flash Attention

- https://github.com/mjun0812/flash-attention-prebuild-wheels/releases

## Radial Attention

- **Windows:**
    - https://github.com/woct0rdho/SpargeAttn/releases

- **Linux:**
    - https://github.com/thu-ml/SpargeAttn

## Older PyTorch

1. Navigate to the WebUI directory
2. Edit the `webui-user.bat` file
3. Add the following command *(in one line ; above the `call webui.bat` line)* to specify the older version:

```bash
set TORCH_COMMAND=pip install torch==2.10.0+cu126 torchvision==0.25.0+cu126 --extra-index-url https://download.pytorch.org/whl/cu126
```

<br>
<br>

## Git

1. Go to **git** 's [Install Page](https://git-scm.com/install/windows)
2. Click on `Git for Windows/x64 Setup` to download the `.exe`
3. Install *(you can leave every option at default)*
4. Verify by running `git` in a console
    - Search `cmd`
    - Type in `git` ; Enter

<p align="center">
<img width=384 src="./assets/tutorials/git.png">
</p>

## UV

0. Prepare a [System Path](#path)
1. Go to **uv** 's [Releases](https://github.com/astral-sh/uv/releases) page
2. Download the `.zip` file for **x64 Windows**
3. Extract the `uv.exe` to your `System Path` folder
4. Verify by running `uv` in a console
    - Search `cmd`
    - Type in `uv` ; Enter

<p align="center">
<img width=384 src="./assets/tutorials/uv.png">
</p>

## FFmpeg

0. Prepare a [System Path](#path)
1. Go to **FFmpeg** 's [Download Page](https://www.ffmpeg.org/download.html)
2. Click on `Windows builds from gyan.dev`

<p align="center">
<img width=384 src="./assets/tutorials/gyan.png">
</p>

3. Download the **essentials** version of `.7z` file

<p align="center">
<img width=384 src="./assets/tutorials/essential.png">
</p>

4. Extract the **3** `.exe` files inside the `bin` folder to your `System Path` folder
5. Verify by running `ffmpeg` in a console
    - Search `cmd`
    - Type in `ffmpeg` ; Enter

<p align="center">
<img width=384 src="./assets/tutorials/ffmpeg.png">
</p>

<br>
<br>

## PATH

> `PATH` refers to folders that the system searches for executables, meaning software in those folders can be launched using just the filename instead of the full absolute path

1. Create a new folder
    - **e.g.** `~\Documents\bin`
2. Open **System Properties**
    - Search `env`

<p align="center">
<img width=384 src="./assets/tutorials/env.png">
</p>

3. Open **Environment Variables**

<p align="center">
<img width=384 src="./assets/tutorials/prop.png">
</p>

4. Click on the **Path** entry ; Click **Edit...**

<p align="center">
<img width=384 src="./assets/tutorials/edit.png">
</p>

5. Click **New** ; Paste in the path to the folder

<p align="center">
<img width=384 src="./assets/tutorials/path.png">
</p>

6. Done!
