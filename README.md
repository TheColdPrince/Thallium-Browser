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

## Contributing

Want to contribute? Great!

[KDE Community Wiki](https://community.kde.org/Get_Involved)

Code review is done on [Phabricator](https://community.kde.org/Infrastructure/Phabricator). When sending patches, add Thallium project (`#Thallium`) as a reviewer.

#### Reporting bugs

You can report any bugs or feature request in KDE [bugzilla](https://bugs.kde.org/enter_bug.cgi?product=Thallium). Before reporting, please make sure your issue isn’t already reported ([open issues](https://bugs.kde.org/buglist.cgi?bug_status=UNCONFIRMED&bug_status=CONFIRMED&bug_status=ASSIGNED&bug_status=REOPENED&component=extensions&component=general&list_id=1597725&product=Thallium)).

#### Contact

You can get in contact with developers using [mailing list](https://mail.kde.org/mailman/listinfo/thallium) or __IRC__ `#thallium` at `irc.libera.chat`.
