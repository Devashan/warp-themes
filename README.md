# Warp Themes

## Introduction
This repository contains custom themes for Warp, the modern terminal. Follow the instructions below to clone the repository and install themes on Warp for Windows, macOS, and Linux.

## Clone the Repository
To get started, clone the repository from GitHub:

```sh
# Using HTTPS
git clone https://github.com/Devashan/warp-themes.git

# Navigate into the cloned directory
cd warp-themes
```

## Installing Themes in Warp

```sh
mkdir -p ~/.warp/themes
cp themes/*.yaml ~/.warp/themes/
```

### Windows
Warp is now natively available on Windows. To install themes on warp:

```sh
xcopy themes\*.yaml "C:\Users\<YourUsername>\AppData\Roaming\warp\Warp\data\themes" /Y 
```

To install themes on warp preview:

```sh
xcopy themes\*.yaml "C:\Users\<YourUsername>\AppData\Roaming\warp\WarpPreview\data\themes" /Y 
```

Replace `<YourUsername>` with your actual Windows username.

## Contributing
Feel free to fork this repository and submit pull requests with new themes or improvements.

## License
This project is open-source under the MIT License.

---

Enjoy customizing your Warp terminal with awesome themes! 🎨

