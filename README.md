# python-boilerplate-repo

A simple python boilerplate to get your projects up and running quickly.

## Table of Contents

-   [Getting Started](#getting-started)
    -   [Prerequisites](#prerequisites)
    -   [Installing](#installing)
-   [Distributing](#distributing)
    -   [Installing packages](#installing-packages)
-   [Customizing](#customizing)
-   [Contributing](#contributing)
-   [Versioning](#versioning)
-   [Authors](#authors)
-   [License](#license)
-   [See also](#see-also)
-   [Acknowledgments](#acknowledgments)

## Getting Started

These instructions will get you a copy of the project up and running on your
local machine for development and testing purposes. See deployment for notes on
how to deploy the project on a live system.

### Prerequisites

You will need python3 and pip3 installed on your machine. You can install it
from the official website https://www.python.org/.

### Installing

A step by step series of examples that tell you how to get a virtual python
environment running:

Clone the git repository

```bash
git clone https://github.com/umcconnell/python-boilerplate-demo.git
```

And navigate into the folder

```bash
cd python-boilerplate-demo/
```

Then create your virtual environment

```bash
python3 -m venv venv
```

Finally, start the virtual environment

```bash
source venv/bin/activate
```

To exit the virtual environment run

```bash
deactivate
```

Happy coding!

## Distributing

### Installing packages

After activating the virtual environment, install your package(s)

```bash
pip3 install <package>
```

Then freeze your packages

```bash
pip3 freeze > requirements.txt
```

## Customizing

Don't forget to edit the [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) files and adding your email address.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) and
[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details on our code of conduct, and
the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available,
see the [tags on this repository](https://github.com/umcconnell/python-boilerplate-repo/tags).

## Authors

Ulysse McConnell - [umcconnell](https://github.com/umcconnell/)

See also the list of
[contributors](https://github.com/umcconnell/python-boilerplate-repo/contributors)
who participated in this project.

## License

This project is licensed under the MIT License - see the
[LICENSE.md](LICENSE.md) file for details.

## See also

Check out the great official [python 3 tutorial](https://docs.python.org/3/tutorial)
and especially [chapter 12](https://docs.python.org/3/tutorial/venv.html) about
virtual environments.

## Acknowledgments

-   [numpy gitignore](https://github.com/numpy/numpy/blob/master/.gitignore) -
    Gitignore inspiration
-   [github python gitignore template](https://github.com/github/gitignore/blob/master/Python.gitignore) - The gitignore template
-   [python3 tutorial](https://docs.python.org/3/tutorial/venv.html) - Guide and
    explanations
-   [VirtualEnv](https://gist.github.com/raulqf/2ca75d7fef2824f03de9761b99b59371) -
    Guide and explanations
-   [python-virtual-environment-howto](https://gist.github.com/simonw/4835a22c79a8d3c29dd155c716b19e16) - Guide and explanations
