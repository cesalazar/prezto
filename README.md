# Carlos' Prezto + Powerlevel10k config — Instantly Awesome Zsh

All the awesomeness of [Prezto][1] preconfigured with [Powerlevel10k][2] prompt;
tailored to suit my needs, and to exclude unused modules to save storage space
and increase install speed.

## Installation

Prezto will work with any recent release of Zsh, but the minimum required
version is **4.3.11**.

01. Launch Zsh:

    ```console
    zsh
    ```

02. Clone the repository:

    ```console
    git clone --depth 1 https://github.com/cesalazar/prezto ~/.zprezto
    ```

03. Init the git submodules and create symlinks to the config files provided
    withe the `install` script. This will remove all the `.git*` files and
    folders by default; pass the `-d` option to preserve them:

    ```console
    ~/.zprezto/install
    ```

    **Note:** If you already have any of the given config files, they will be
    automatically backed up into a `.tar` archive in the directory of this
    repository, and then replaced.

04. Set Zsh as your default shell:

    ```console
    chsh -s /bin/zsh
    ```

05. Open a new Zsh terminal window or tab, or `source ~/.zshrc` in the current
    session.

For any other information please check [Prezto][1].

## Usage

This fork has enabled only the features I need. Read the source code and the
accompanying README files to learn about what is available.

## License

This project is licensed under the MIT License.

[1]: https://github.com/sorin-ionescu/prezto
[2]: https://github.com/romkatv/powerlevel10k
