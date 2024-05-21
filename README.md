# twm-utils
<b>twm-utils</b> is a simple program to improve twm (Tom's window manager) including move to workspaces with mouse scrolling and keybinding. It's also possible to move window into another workspace.

## Introduction
<b>twm-utils dosn't</b> add new fitures to twm. This is just simple program that allows you to manage windows and move between workspaces by taking advantage of <b>vdesk</b> and <b>xdotool</b>.

## Installation 
Before you install <b>twm-utils</>, you need to install <b>vdesk</b> and <b>xdotool</b> on your system. On Debian run:
```
sudo apt install vdesk xdotool
```
Then clone this repository on your directory, and open it:
```
git clone https://github.com/diws1/twm-utils
cd twm-utils/
```
Run the installation:
```
make
sudo make install
```
