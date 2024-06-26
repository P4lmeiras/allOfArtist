# All Of Artist
[Spicetify](https://github.com/khanhas/spicetify-cli) extension to create a playlist with all songs of an artist

## Install
### Through [marketplace](https://github.com/spicetify/spicetify-marketplace)
In Extensions, search for 'All Of Artist' and install it.

### Manually
Copy `allOfArtist.js` into your [Spicetify](https://github.com/khanhas/spicetify-cli) extensions directory:
| **Platform**   | **Path**                                                                             |
|----------------|--------------------------------------------------------------------------------------|
| **Linux**      | `~/.config/spicetify/Extensions` or `$XDG_CONFIG_HOME/.config/spicetify/Extensions/` |
| **MacOS**      | `~/spicetify_data/Extensions` or `$SPICETIFY_CONFIG/Extensions`                      |
| **Windows**    | `%appdata%\spicetify\Extensions\`                                                    |

After putting the extension file into the correct folder, run the following command to install the extension:

```sh
spicetify config extensions allOfArtist.js
spicetify apply
```

Or you can manually edit your `config-xpui.ini` file. Add your desired extension filenames in the extensions key, separated them by the | character:

```ini
[AdditionalOptions]
...
extensions = foo.js|bar.js|allOfArtist.js
```

Then run:

```sh
spicetify apply
```

## Usage
Right click an artist, track or album and in "Create All Of [Artist Name]" there will be 2 options:
  - With Featured On - Will create a playlist with all songs that the artist is featured on (given that spotify acknowledges it as such);
  - Only Originals - Will create a playlist with only the songs shown in the artist's profile.

<div float='left'>
<img src='https://raw.githubusercontent.com/P4lmeiras/allOfArtist/main/allOfArtistMenu.png' width=400><br>
<img src='https://raw.githubusercontent.com/P4lmeiras/allOfArtist/main/allOfArtistNotification.png' width=400>
</div>

## More

If you find any bugs, please [create a new issue](https://github.com/P4lmeiras/allOfArtist/issues/new) on the GitHub repo.
To better assess the issue please provide:
  - The spicetify's version,
  - All extensions installed besides allOfArtist,
  - And if the issue is related to some specific artists, provide those aswell.

[![Github Stars Badge](https://img.shields.io/github/stars/P4lmeiras/allOfArtist?logo=github&style=flat&color=yellow)](https://github.com/P4lmeiras/allOfArtist/stargazers)
[![Github Issues Badge](https://img.shields.io/github/issues/P4lmeiras/allOfArtist?logo=github&style=flat&color=green)](https://github.com/P4lmeiras/allOfArtist/issues)
