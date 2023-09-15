# Django URL Shortener

A URL shortener web application built with Django.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Django URL Shortener is a robust web application that allows you to create shortened versions of long URLs. It's powered by Django, a high-level Python web framework, making it easy to manage and extend.

## Features

- Shorten long URLs into concise, easy-to-share links.
- Redirection to the original URL when users access the shortened link.
- User account system to manage and track shortened URLs.
- Statistics tracking: monitor the number of clicks on each shortened URL.
- URL expiration: set expiration dates for shortened links.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following requirements met:

- Python 3.x installed on your system.
- [Django](https://www.djangoproject.com/) web framework installed. You can install it using `pip`:

  ```bash
  pip install Django
## Authors

- [@ermiasgw](https://github.com/ermiasgw)


## Badges


[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)



## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Installation

Clone the repository

```bash
git clone https://github.com/ermiasgw/url_shortner.git
cd url_shortner

```

Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

Install project dependencies
```bash
pip install -r requirements.txt
```

Run database migrations
```bash
python manage.py migrate
```

Start the development server
```bash
python manage.py runserver
```
    
