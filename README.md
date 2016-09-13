
# PlayBar2

MPRIS2 client, written in QML for **Plasma 5** and **GNU/Linux**.

<img src="https://github.com/audoban/PlayBar2/blob/remotes/origin/playbar-devel/playbar_vertical_layout.png" width="300"></img> <img src="https://github.com/audoban/PlayBar2/blob/remotes/origin/playbar-devel/playbar_slider_seek.png"></img>

# Installation
## Build from the source code
**Dependencies:** `plasma-framework-devel plasma5-workspace-devel kdeclarative-devel kglobalaccel-devel kconfigwidgets-devel kxmlgui-devel kwindowsystem-devel kdoctools-devel extra-cmake-modules`

**Dependencies for OpenSUSE:**
```
sudo zypper install gcc-c++ plasma-framework-devel plasma5-workspace-devel kdeclarative-devel \
kglobalaccel-devel kconfigwidgets-devel kxmlgui-devel kwindowsystem-devel kdoctools-devel \
extra-cmake-modules
```
**Dependencies for Kubuntu:**
```bash
sudo apt-get install g++ plasma-framework-dev plasma-workspace-dev libkf5declarative-dev \
libkf5globalaccel-dev libkf5configwidgets-dev libkf5xmlgui-dev \
libkf5windowsystem-dev kdoctools-dev cmake extra-cmake-modules kdelibs5-dev
```

Create a *build* directory into **PlayBar**, compile the Plasmoid and enjoy it.

**OpenSUSE:**
```bash
mkdir build && cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr -DKDE_INSTALL_LIBDIR=lib64/qt5 -DCMAKE_BUILD_TYPE=Release ..
make && sudo make install
```
**Kubuntu:**
```bash
mkdir build && cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr -DCMAKE_BUILD_TYPE=Release ..
make && sudo make install
```

## Repositories
**Kubuntu:**
```bash
sudo add-apt-repository ppa:varlesh-l/plasma5-tools
sudo apt-get update
sudo apt-get install plasma-widget-playbar2
```

**Arch Linux (AUR):**
```bash
yaourt kdeplasma-applets-playbar2
```

## Configure keyboard shortcuts
PlayBar also supports keyboard shortcuts and these come with a default configuration, but if you want change you must go to preferences of PlayBar.

![Shortcuts](https://raw.githubusercontent.com/audoban/PlayBar2/master/playbar_keys.png)

# Help me to translate!
**If you want to add a language, please follow this**  __[Thread.](https://github.com/audoban/PlayBar2/issues/1)__

# Contributors
- ![Alexey Murz Korepov](https://github.com/MurzNN) Improve Readme
- ![varlesh](https://github.com/varlesh) Create a PPA repository with Packages for **Ubuntu**
- ![André Vitor de Lima Matos](https://github.com/andrevmatos) Create a AUR package for **Arch Linux** and Portuguese translation
- ![Tomasz Przybył](https://github.com/FadeMind) Polish translation
- ![Konstantin](https://github.com/KottV) Russian translation
- ![dkadioglu](https://github.com/dkadioglu) German translation
- ![tillschaefer](https://github.com/tillschaefer) Gentoo ebuild

# See the ![Milestones](https://github.com/audoban/PlayBar2/milestones)!
