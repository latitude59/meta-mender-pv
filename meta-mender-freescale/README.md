# meta-mender-freescale

This Yocto layers contains recipes which enables support of building Mender client for boards in the meta-freescale layer.

## Dependencies

This layer depends on:

    URI: git://git.yoctoproject.org/git/meta-freescale
    branch: rocko
    revision: HEAD

in addition to `meta-mender` dependencies.

## Build instructions

- Read [the Mender documentation on Building a Mender Yocto image](https://docs.mender.io/Artifacts/Building-Mender-Yocto-image) for Mender specific configuration.
- Set MACHINE to one of the following
    - imx7dsabresd
    - (others may work but are untested.
- Run `bitbake <image name>`
