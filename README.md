# Deeper Down updates

**Download the latest from [Releases](https://github.com/SnowberriFox/Deeper-Down-Updates/releases).** Early-access builds are marked pre-release.

Deeper Down is the dungeon (`deeperdown-X.jar`). It works on its own or alongside PokéShift.

`update.json` is what the game reads to tell players there's a newer build (a toast on the title screen and a chat line with a link when they join):

- `promos."1.21.1-latest"`: the newest build, early access included. EA players are told about it.
- `promos."1.21.1-recommended"`: the newest stable build. Everyone is told about it.
- `"1.21.1"`: a one-line note per version, shown with the notice.

Releases from before this repo existed (up to Deeper Down 3.0.1) are in [Pokeshift-updates](https://github.com/SnowberriFox/Pokeshift-updates/releases).
SnowberriLib is needed by every mod: [SnowberriLib-Updates](https://github.com/SnowberriFox/SnowberriLib-Updates/releases).

Keep the repo public so games can read `update.json`. The code lives in the private PokeShift repo.
