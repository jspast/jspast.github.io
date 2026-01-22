# jspast.github.io

## Development

### Install zola

```sh
flatpak install flathub org.getzola.zola
```

To use `zola` directly, add an alias as described in the [official documentation](https://www.getzola.org/documentation/getting-started/installation/#flatpak).

### Clone the repo

Tabi is used as a git submodule.

Clone with submodules:

```sh
git clone --recurse-submodules git@github.com:jspast/jspast.github.io.git
```

Or init submodules after cloning:

```sh
git submodule update --init --recursive
```

### Update submodules

```sh
git submodule update  --recursive --remote
```

### Start the website locally

```sh
zola serve
```