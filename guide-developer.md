# Developer Guide

## Table Of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Settings](#settings)

### Requirements

Built with the Django Framework and using Python `2.7`, so we strongly recommend using a UNIX-like OS.
No other requirement is needed.

### Installation

Setup environment with [virtualenv](https://virtualenv.pypa.io) and [pip](https://pip.pypa.io).

```bash
# Create new virtualenv
$ virtualenv litrusenv

$ source litrusenv/bin/activate
```

Clone the project.

```bash
# Get it.
(litrusenv)$ git clone https://github.com/litrus/litrus.git
(litrusenv)$ cd litrus/
# Install Django and other dependencies.
(litrusenv)$ pip install -r requirements.txt
```

Create the configuration file, open it and ensure everything its ok.

```bash
(litrusenv)$ cp config.py.example config.py
```

 Run database migrations.
 
 ```bash
(litrusenv)$ python manage.py migrate
```
