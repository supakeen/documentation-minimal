# Fedora Minimal Documentation

This is the build repository for the Fedora Minimal Documentation Websites. The latest published version of these sites can be found at [Fedora Minimal Docs](https://docs.fedoraproject.org/en-US/minimal/) and [Fedora Minimal SIG Docs](https://docs.fedoraproject.org/en-US/minimal-sig/). Please report issues any issues with the Fedora Minimal documentation, or submit pull requests in this repository.

The Fedora Minimal documentation is built using [Antora](https://antora.org). General details for getting started can be found on the main Fedora Project [documentation guide](https://docs.fedoraproject.org/en-US/fedora-docs/contributing-docs/).

## Testing your changes locally

Building and previewing is done in containers and should work on any machine that has `podman` or `docker` available.

**To build the site**, run:

```bash
$ ./build.sh
```

Please note the build script uses Docker to build the site in an isolated environment.
You might be asked for a root password in order to run it.

The result will be in a `./public/` directory.

**To preview the site**, either open the `./public/en_US/index.html` file in a web browser, or run:

```bash
$ ./preview.sh
```

