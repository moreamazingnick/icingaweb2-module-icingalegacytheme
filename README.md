# Icinga Legacytheme

1. [About](#about)
2. [License](#license)
3. [Installation](#installation)
4. [Contributing](#contributing)

## About

**icingaweb2-module-icingalegacytheme** is drawn from the last release of the official icinga-legacy.less.
* It is light mode only
* It is optimized for fash color change
* There is a second theme referencing icinga-legacy named icinga-legacy-nosocial, which hides all social media buttons

## License

icingaweb2-module-legacytheme is licensed under the terms of the GNU
General Public License Version 2, you will find a copy of this license in the
COPYING file included in the source package.

## Installation

Install these theme repository like any other Icinga Web 2 theme:

* copy all folders/files to your icingaweb2 folder (mostly /usr/share/icingaweb2)
    
```bash
wget https://github.com/moreamazingnick/icingaweb2-module-icingalegacytheme/archive/refs/tags/v1.0.0.zip
unzip v1.0.0.zip -d /usr/share/icingaweb2/modules
mv /usr/share/icingaweb2/modules/icingaweb2-module-icingalegacytheme /usr/share/icingaweb2/modules/icingalegacytheme
chmod -r 755 /usr/share/icingaweb2/modules/icingalegacytheme
chown -R root:root /usr/share/icingaweb2/modules/icingalegacytheme
icingacli module enable icingalegacytheme
```

## Contributing

Every contribution is appreciated!
