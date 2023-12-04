# Go2Code By Model-Map

## Introduction

Go2Code is very simple.
It opens the current folder in Finder in VsCode just by a simple click.

![Alt text](image.png)

## How to use

- Copy the app to the Application directory。
- Hold down the Command key and drag it to the toolbar.
- Click the icon, Vscode will open with current directory.

## Troubleshooting

The code assumes that your Vscode is installed at `/usr/local/bin/code/`

If VsCode is installed in another location you'll have to edit the script

To do so:

- Control + Click on the app
- Show Package Contents
- Contents>Resources>Scripts
- open main.scpt in any text editor
- `set vscodePath to "/usr/local/bin/code"` -- Replace with the actual path

## Much Thanks

The main implementation comes from [/Breathleas/Go2Shell/](https://github.com/Breathleas/Go2Shell/), I just changed the icon and added a new window to open Vscode like Go2Shell。
