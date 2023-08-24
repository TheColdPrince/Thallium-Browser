# Thallium

Thallium is a KDE web browser. It uses QtWebEngine rendering engine.


## Downloads

Thallium downloads are available from [homepage](https://www.thallium.org/download/).

## Building

```sh
mkdir build && cd build
cmake ..
make && make install
```

### Install to custom prefix

When installing Thallium to custom prefix, you may need to adjust `XDG_DATA_DIRS` environment variable.

```sh
# Build
cmake -DCMAKE_INSTALL_PREFIX=$HOME/thallium

# Run
export XDG_DATA_DIRS="$HOME/thallium/share:$XDG_DATA_DIRS"
$HOME/thallium/bin/thallium
```
