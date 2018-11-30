# [Toxin](https://packagecontrol.io/packages/Theme%20-%20Toxin)

A colorful theme and color scheme for the [Sublime Text](//sublimetext.com/) editor.

![Screenshot](https://cloud.githubusercontent.com/assets/26496/19066717/e92fd1a6-8a1a-11e6-812d-0a702ef55fbd.png)
Git status in sidebar (uncollapsed vs collapsed directories with modified content):

![Git sidebar, uncollapsed](https://user-images.githubusercontent.com/26496/49298983-f23f5300-f4be-11e8-91a7-9e0ecd0cd6a4.png)
![Git sidebar, collapsed](https://user-images.githubusercontent.com/26496/49298987-f4091680-f4be-11e8-866a-a5d6a36c719c.png)

## Options

`use_minimap_as_scrollbar`:

- Use the minimap as the vertical scrollbar, hides the normal vertical scrollbar.
- Requires `always_show_minimap_viewport` setting to be `true`.

`mouse_wheel_switches_tabs`:

- Enables scrolling through tabs with the mouse wheel.
- Requires `enable_tab_scrolling` setting to be `false`.

`hide_sidebar_heading`:

- Hides the headers in the sidebar.
- Works best when _not_ showing open files, only file/project tree.

`highlight_modified_tabs`:

- Shows an indicator on the tabs if a file is dirty (changed, unsaved).

`hide_gutter_unfolded`:

- Hides unfolded (-) icons in the gutter (unless hovering them).

`show_tab_close_buttons`:

- Shows close tab buttons (enabled by default).

## Installation

##### Using the package manager

1. Install the [Sublime Text Package Control](//packagecontrol.io/installation) plugin if you haven't already.
2. Open up the command palette (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>) and enter `Package Control: Install Package`
3. Search for `Theme - Toxin` and hit <kbd>Enter</kbd> to install.
4. Follow the instructions that appears on the screen.

##### Manual installation with Git

1. Click the `Preferences > Browse Packages` menu.
2. Open up a terminal and execute the following:
 - `git clone https://github.com/p3lim/sublime-toxin Theme\ -\ Toxin`
3. Restart Sublime Text and apply the theme and color in the settings.
