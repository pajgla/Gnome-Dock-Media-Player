# Media Widget for Dash to Dock
This is a simple GNOME Shell Extension that integrates a media widget directly into your Dash to Dock panel.

<img width="1091" height="91" alt="image" src="https://github.com/user-attachments/assets/f12f3f31-0602-47f9-8b65-9ee131ce113f" />

## Features
- **Media Controls**: Play/Pause, Skip and Previous buttons embedded in the dock
- **Track Information**: Shows information about your current media
- **Adaptive UI**: Widget's background color dynamically changes to match the dominant color of current album art
- **Adaptive Layout**: Automatically expands or shrinks based on the length of artist and track name, to keep the dock tidy
- **Adaptive Visibility**: Automatically hides from the dock when no media is being played

## Requirements
- GNOME Shell 49 (previous versions not tested, but it should work)
- **Dash To Dock** extension (support for native dock coming soon)

# Installation

## Manual Instalation
1) **Clone the repository**
   ```
   git clone https://github.com/pajgla/Gnome-Dock-Media-Player-Extension
   ```
2) **Install the extension**:
   ```
   cd ~/.local/share/gnome-shell/extensions/ && \
   git clone https://github.com/pajgla/Gnome-Dock-Media-Player-Extension.git dock-media-player@pajgla.github
   ```
3) **Restart GNOME Shell**:
   - X11: Press `Alt+F2`, type `r` and hit `Enter`
   - Wayland: Log out and log back in
4) **Enable the Extensin**:
   ```
   gnome-extension enable dock-media-player@pajgla.github
   ```

# Contributing

All contributions are welcome! Whether it's a bug fix, a new feature or an improvement, feel free to help out.

If you'd like to contribute:
1) Fork the repository
2) Create a new branch
3) Commit your changes
4) Open a pull request

If you have ideas but aren't sure where to start, feel free to open an Issue to discuss them first

# More Examples

![output](https://github.com/user-attachments/assets/0f992854-3fd8-491b-9b70-859a7cef2c41)

![output](https://github.com/user-attachments/assets/09baaee4-0e99-4c86-aef1-236f3d2bbee9)


