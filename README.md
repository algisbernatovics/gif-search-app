# GIF Search App

A PHP web app for searching and displaying GIF results through a templated interface.

## Overview

A PHP web app for searching and displaying GIF results through a templated interface.

## Preview

![GIF Search preview](./preview.png)

## Features

- Uses Guzzle for external API requests.
- Routes requests with FastRoute.
- Renders views with Twig templates.
- Stores or records search results through model classes.
- Includes a preview image.

## Tech Stack

- PHP
- Composer
- Guzzle
- FastRoute
- Twig
- Dotenv

## Project Structure

- `index.php` - application entry point
- `router.php` - local development router
- `app/Controller/` - request controller
- `app/Models/` - API and result handling
- `app/Views/` - Twig templates

## Getting Started

Install dependencies and serve locally:

```bash
composer install
php -S localhost:8000 router.php
```

Copy `.envExample` to `.env` and add any required API credentials.

## Portfolio Notes

- Shows a small MVC-style PHP app without a heavy framework.
- Demonstrates API consumption, routing, and templating.

## Status

Portfolio-ready PHP web app.

## License

MIT License. See [LICENSE](./LICENSE).
