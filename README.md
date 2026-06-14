<p align="center">
  <img src="assets/logo.svg" alt="Taskbar Media Controller" width="128" />
</p>

<h1 align="center">Taskbar Media Controller</h1>

<p align="center">
  A sleek taskbar widget that shows your currently playing music with playback controls for Windows 10/11.
</p>

<p align="center">
  <a href="#installation">Installation</a> • <a href="#features">Features</a> • <a href="#configuration">Configuration</a>
</p>

## Features

- **Now Playing** - Displays song title, artist, and album art from any app using Windows media transport controls (Spotify, YouTube Music, Tidal, etc.)
- **Playback Controls** - Previous, play/pause, and next buttons with hover animations
- **Volume Control** - Adjust system volume using mouse wheel while hovering over the panel
- **Progress Bar** - Thin progress bar at the bottom showing playback position with smooth interpolation
- **Song Transition Animation** - Smooth fade animation when the song changes (4 transition types)
- **Multi-Monitor Support** - Shows on the taskbar of the active monitor
- **Album Art** - Shows album artwork with rounded corners, or a music note placeholder when unavailable
- **Auto Theme** - Automatically switches text color between light and dark based on your Windows theme
- **Album Color Mode** - Extracts the dominant color from album art for text/icons
- **Acrylic Background** - Optional frosted glass effect with adjustable opacity
- **Scrolling Text** - Long song titles scroll automatically when they don't fit
- **Hide in Fullscreen** - Optionally hides the panel when a fullscreen app is active
- **Idle Timeout** - Auto-hide after a configurable period of no playback
- **Customizable** - Adjust size, position, font size, button scale, and colors

## Usage

1. Enable the mod and the widget will appear on your taskbar
2. Hover over the panel to reveal playback controls
3. Click the buttons to control media playback
4. Click on the progress bar to seek to a different position
5. Use mouse wheel to adjust system volume while hovering over the panel
6. Adjust settings in the Windhawk UI to customize appearance and behavior

## Requirements

- Windows 10/11 with taskbar
- [Windhawk](https://windhawk.net/)
- A media app that supports Windows media transport controls (most modern music/video players)

## Installation

1. Install [Windhawk](https://windhawk.net/)
2. Open Windhawk and search for "Taskbar Media Controller" in the mod library
3. Click Install and enable the mod

### Manual Installation

1. Download `taskbar-media-controller.wh`
2. Open Windhawk, go to **Mods** tab
3. Click **Create new mod**
4. Paste the contents of the `.wh` file and save

## Configuration

All settings are available in the Windhawk mod settings panel:
- **Panel size** - Width and height in pixels
- **Position** - X/Y offset from the taskbar edge
- **Theme** - Auto, manual hex color, or album art color
- **Background** - Acrylic blur opacity (0-255)
- **Buttons** - Scale factor (0.5x to 4.0x)
- **Progress Bar** - Show/hide, height, fill/track opacity
- **Animations** - Transition type (fade, slide, zoom, flip), speed
- **Scrolling** - Speed, delay before scrolling starts
- **Volume** - Mouse wheel step size (1-20%)
- **Multi-Monitor** - Show on active monitor's taskbar
- **Hide in Fullscreen** - Auto-hide when a fullscreen app is active
- **Idle Timeout** - Auto-hide after N seconds of no playback

## License

MIT
