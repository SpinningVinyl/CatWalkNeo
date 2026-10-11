> [!NOTE]
> CatWalk Neo is based on the CatWalk plasmoid from https://store.kde.org/p/2055225/ and https://store.kde.org/p/2137844/. The original CatWalk has been a user favourite for a very long time; this fork aims to update it while respecting its legacy.

# CatWalk Neo

A simple plasmoid showing the total CPU usage. Visually similar to RunCat.

|animated preview|preview|
|:-:|:-:|
|![animated preview](https://images.pling.com/img/00/00/52/72/79/2137844/catwalk.gif)|![preview](https://images.pling.com/img/00/00/52/72/79/2137844/screenshot-20230623-1500192.png)|

Special thanks to [Nikita Beloglazov](https://github.com/NikitaBeloglazov) for the animated preview!

## Installation

Requires KDE Plasma 6.

```sh
git clone https://github.com/SpinningVinyl/CatWalkNeo.git
cd CatWalkNeo
kpackagetool6 --type Plasma/Applet --install ./org.kde.plasma.catwalk-neo/
```

To upgrade an existing installation (from the CatWalkNeo checkout directory):

```sh
git pull
kpackagetool6 --type Plasma/Applet --upgrade ./org.kde.plasma.catwalk-neo/
```
