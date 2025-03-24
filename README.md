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

### macOS & Linux
1. Open Warp.
2. Click on `Settings` (⚙️ icon) in the top-right corner.
3. Navigate to the `Appearance` section.
4. Click `Import Theme`.
5. Select the `.yaml` theme file from the cloned `warp-themes` directory.
6. Apply the theme.

Alternatively, you can manually move the themes to Warp’s config folder:

```sh
mkdir -p ~/.warp/themes
cp themes/*.yaml ~/.warp/themes/
```

### Windows
Warp is now natively available on Windows. To install themes:

1. Open Warp.
2. Click on `Settings` (⚙️ icon) in the top-right corner.
3. Navigate to the `Appearance` section.
4. Click `Import Theme`.
5. Select the `.yaml` theme file from the cloned `warp-themes` directory.
6. Apply the theme.

Alternatively, you can manually copy the themes to Warp’s theme folder:

```sh
xcopy themes\*.yaml "C:\Users\<YourUsername>\AppData\Roaming\warp\Warp\data\themes" /Y
```

Replace `<YourUsername>` with your actual Windows username.

## Contributing
Feel free to fork this repository and submit pull requests with new themes or improvements.

## License
This project is open-source under the MIT License.

---

Enjoy customizing your Warp terminal with awesome themes! 🎨

# NOTE: AI Generated README *
