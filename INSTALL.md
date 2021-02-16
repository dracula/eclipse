### [Eclipse](https://www.eclipse.org/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    $ git clone https://github.com/dracula/eclipse.git

Note: You will need to change theme and reimport `dracula-theme.xml` to update theme in Eclipse.

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/eclipse/archive/master.zip) option and unzip them.

#### Prerequisites

- [Eclipse](https://www.eclipse.org/) IDE installed on your system.
- [Darkest Dark](https://marketplace.eclipse.org/content/darkest-dark-theme-devstyle) plugin from the Eclipse Marketplace.

#### Activating theme

1. In Eclipse, to open the desired theme selection window go to `Window > Preferences > DevStyle > Color Theme`.
2. In Extras section, click import and select `dracula-theme.xml` from the downloaded repository.
3. Select `Dracula Theme` from the Editor theme dropdown.
4. Select `Dark Custom` from the Workbench Theme dropdown.
5. Check `Theme background` in Extras section.
6. Enter the HSL values of `HSL(231, 15, 18)` (equivilent of #282a36 - background).
7. Restart Eclipse.

> See Screenshot for clarifications below.

![Eclipse Configuration](https://raw.githubusercontent.com/dracula/eclipse/master/configuration.png)

#### Touble shooting

- If the HSL selection menu does not appear for Window theme `Dark Custom`, try restarting Eclipse and reopening the menu.
