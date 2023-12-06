
# discord-bot
[![Tests](https://github.com/ITeapotPL/discord-bot/actions/workflows/test.yml/badge.svg)](https://github.com/ITeapotPL/discord-bot/actions/workflows/test.yml)
[![Coverage](https://coverage-badge.samuelcolvin.workers.dev/ITeapotPL/discord-bot.svg)](https://coverage-badge.samuelcolvin.workers.dev/redirect/ITeapotPL/discord-bot)
[![Poetry](https://img.shields.io/endpoint?url=https://python-poetry.org/badge/v0.json)](https://python-poetry.org/)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![Code style](https://img.shields.io/badge/code%20style-black-000000.svg?label=Code%20style)](https://github.com/psf/black)
[![License](https://img.shields.io/github/license/ITeapotPL/discord-bot.svg?label=License)](https://github.com/ITeapotPL/discord-bot/blob/HEAD/LICENSE)
[![Pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)

A Discord Bot for the ITeapot team. Powered by hikari, crescent & miru.

# Installation for contributors



> [!Note]
> If you use Windows, it is highly recommended to complete the installation in the way presented below through [WSL2](https://learn.microsoft.com/en-us/windows/wsl/install).



1.  Fork the [discord-bot repository](https://github.com/ITeapotPL/discord-bot) on GitHub.

1.  [Install Poetry](https://python-poetry.org/docs/#installation).<br/>
    Poetry is an amazing tool for managing dependencies & virtual environments, building packages and publishing them.
    You might use [pipx](https://github.com/pypa/pipx#readme) to install it globally (recommended):

    ```shell
    pipx install poetry
    ```

    <sub>If you encounter any problems, refer to [the official documentation](https://python-poetry.org/docs/#installation) for the most up-to-date installation instructions.</sub>

    If you want to use pipx to install dev dependencies as well, install the [poetry apps](https://github.com/bswck/poetry-apps#readme) plugin:
    ```shell
    pipx inject poetry poetry-apps
    ```

    Be sure to have Python 3.10 installed—if you use [pyenv](https://github.com/pyenv/pyenv#readme), simply run:

    ```shell
    pyenv install 3.10
    ```

1.  Clone your fork locally and install dependencies.

    ```shell
    git clone https://github.com/your-username/discord-bot path/to/discord-bot
    cd path/to/discord-bot
    poetry env use $(cat .python-version)
    poetry install
    ```

    Next up, simply activate the virtual environment and install pre-commit hooks:

    ```shell
    poetry shell
    pre-commit install --hook-type pre-commit --hook-type pre-push
    ```

For more information on how to contribute, check out [CONTRIBUTING.md](https://github.com/ITeapotPL/discord-bot/blob/HEAD/CONTRIBUTING.md).<br/>
Always happy to accept contributions! ❤️


# Legal info
© Copyright by ITeapot ([@ITeapotPL](https://github.com/ITeapotPL)).
<br />This software is licensed under the terms of [GPL-3.0 License](https://github.com/ITeapotPL/discord-bot/blob/HEAD/LICENSE).
