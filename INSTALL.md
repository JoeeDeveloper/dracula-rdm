### [Remote Desktop Manager](https://devolutions.net/remote-desktop-manager)

#### Install using Git

If you are a Git user, you can install the theme and keep it up to date by cloning the repo:

```bash
git clone https://github.com/dracula/remote-desktop-manager.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/remote-desktop-manager/archive/main.zip) option and unzip it.

#### Activating theme

The theme is a terminal color scheme file, `Dracula.txt`, in Remote Desktop Manager's own export format.

To apply it to every terminal session:

1. Open **File > Settings > Terminal > Types**;
2. Click **Import** under the color scheme and select `Dracula.txt`;
3. Open or reconnect an SSH session. Boom! It's working ✨

To apply it to a single entry instead:

1. Edit the SSH Shell entry and go to its terminal settings;
2. Set **Colors** to **Override**;
3. Click **Import color scheme** and select `Dracula.txt`.
