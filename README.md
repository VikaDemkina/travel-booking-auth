# Travel Booking Auth Microfrontend

This repository contains the authentication microfrontend for the Travel Booking application, built with Vue.js.

## Installation

```bash
npm install
```

## Development

```bash
npm run serve
```

## Build

```bash
npm run build
```

## Features

- User authentication (login, register)
- Session management
- Authorization controls
- Profile management

## Architecture

This is part of a microfrontend architecture using:
- Vue.js for the framework
- Vuex for state management
- Single-spa for microfrontend integration

## CI/CD

This repository uses GitHub Actions for CI/CD pipeline, which will:
- Build and test the code on every PR and push to main
- Collect build metrics
- Deploy to GitHub Pages on push to main