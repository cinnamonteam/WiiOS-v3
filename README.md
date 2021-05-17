# WiiOS-v3

A new PPTOS created by the Cinnamon Team (formerly known as the PieOS Team).

## Releases

You can find prebuilt releases [here](https://github.com/cinnamonteam/WiiOS-v3/releases/).

## Compiling

<details>
<summary>If you don't want to use the terminal to clone this repository, click here</summary>

Click `Code > Download ZIP` at the top of this repository, like the image below:

[![Image](./src/readme/images/DownloadZIP.svg)](https://github.com/cinnamonteam/WiiOS-v3/archive/refs/heads/master.zip)

or [click here for a direct ZIP download.](https://github.com/cinnamonteam/WiiOS-v3/archive/refs/heads/master.zip)

Unzip the file and open the `src` directory.
</details>

Open your terminal and clone this repository.

```batch
git clone https://github.com/cinnamonteam/wiios-v3
```

Go into the `src` directory.

```batch
cd wiios-v3/src
```

Make sure you have [7-Zip](https://www.7-zip.org/) installed, then run this command below:

### For `pptx`, use this command

```batch
7z a "WiiOS_Build1.pptx" -tzip -mm=Deflate -mx=1 ./pptx/* 
```

### For `pptm`, use this command

```batch
7z a "WiiOS_Build1.pptm" -tzip -mm=Deflate -mx=1 ./pptm/* 
```
