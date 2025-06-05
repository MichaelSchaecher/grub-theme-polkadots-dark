<div align="center">
  <h1
    style="font-size: 3rem; font-weight: bold; color: rgb(150, 108, 190);"
    >
    Dark Polka Dot Theme
  </h1>
  <h3>
    A dark theme for the Grub bootloader with a polka dot background.
  </h3>
</div>

  The default theme for the Grub bootloader is quite bland, so I decided to create a dark theme with a polka dot background. This theme is inspired by the themes found on [Grub Themes](https://www.gnome-look.org/browse?cat=109&ord=latest), none of which fit what I was looking for, so I made my own.

<div align="center">
  <h2>Installation</h2>
</div>

There are two ways to install the theme: using the **APT** package manager or manually. The APT method is recommended for ease of use and automatic updates. To install the theme using APT go the [repository](https://repository.howtonebie.com) landing page and follow the instructions there.

<div align="center">
  <h3>Manual Installation</h3>
</div>

To install the theme, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/MichaelSchaecher/grub-theme-polkadots-dark.git
    ```

2. Copy the theme to the Grub themes directory:

    ```bash
    mkdir -p /usr/share/grub/themes/polkadots-dark
    sudo cp -av ./{fonts,images,icons,theme.txt} /usr/share/grub/themes/polkadots-dark/
    ```

<div align="center">
  <h2>Collaboration</h2>
</div>

If you would like to contribute to the theme, feel free to open a pull request. If you have any suggestions or issues, please open an issue on the GitHub [repository](https://github.com/MichaelSchaecher/grub-theme-polkadots-dark/issues) issue tracker page.
