# CS-yonkou-plugins

CloudStream 3 extension repository by **yonkou** — multi-language movie, series, live TV, anime and audiobook providers.

## Install

In CloudStream: Settings → Extensions → Add repository, then paste:

```
https://raw.githubusercontent.com/yonkou0/CS-yonkou-plugins/builds/plugins.json
```

Install any provider from the list. Updates are delivered automatically — every push to `main` rebuilds all extensions and refreshes the `builds` branch.

## Requirements

- [CloudStream 3](https://recloudstream.github.io/csdocs/) (free, open-source)

## Providers

Movies, series, live TV, radio, anime, and audiobooks across Tamil, Hindi, Telugu, Bengali, English and more. See the repository list in-app for the full set of 26 extensions.

## Build locally

```
./gradlew makePluginsJson
```

Each provider can also be built individually: `./gradlew :ProviderName:make` produces `ProviderName/build/ProviderName.cs3`.

## License

GNU GPL v3 or later. These extensions fetch content from third-party sites in the same way a browser does; no content is hosted here.
