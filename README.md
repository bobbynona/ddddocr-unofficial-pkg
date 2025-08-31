# ddddocr-unofficial

> **Note: This is an unofficial PyPI release.**
>
> This package, `ddddocr-unofficial`, is an unofficial release of `ddddocr` version 1.6.0. It is maintained by the community to provide an up-to-date, installable version of the original source code.
>
> All credit for the software belongs to the original author, **sml2h3**.
>
> - **Original GitHub Repository:** [https://github.com/sml2h3/ddddocr](https://github.com/sml2h3/ddddocr)
> - **This PyPI Package:** [https://pypi.org/project/ddddocr-unofficial/](https://pypi.org/project/ddddocr-unofficial/)
>
> Please report any issues related to this specific PyPI package to its fork repository, not the original author's issue tracker.

---

## About

This package provides the 1.6.0 version of `ddddocr` for easy installation via PyPI.

## Documentation

For complete documentation on installation, usage, and API details, please refer to the original author's README file, which has been included in this package.

**[Click here to view the original README](./ddddocr/README.md)**

---

## Building from Source

This repository uses a Git submodule to include the original `ddddocr` source code. To build the package yourself, follow these steps:

1.  **Clone the repository with submodules:**
    ```bash
    git clone --recurse-submodules https://github.com/bobbynona/ddddocr-unofficial-pkg.git
    cd ddddocr-unofficial-pkg
    ```
    If you have already cloned the repository without the submodules, you can initialize them with:
    ```bash
    git submodule update --init --recursive
    ```

2.  **Install `uv` (if you haven't already):**
    `uv` is used for building the package.
    ```bash
    pip install uv
    ```

3.  **Build the package:**
    This command will create the installable `.whl` and `.tar.gz` files in the `dist/` directory.
    ```bash
    uv build
    ```