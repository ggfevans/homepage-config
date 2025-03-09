# Homepage Configuration

My personal configuration for [Homepage](https://gethomepage.dev), a modern self-hosted dashboard.

## Features

- Dark theme with Slate color scheme
- Custom widgets including:
  - System resources monitoring
  - Weather display
  - Tailscale integration
  - Date/time and greeting
- Organized service sections:
  - System management
  - Media services
  - Utilities
  - Backups
  - Downloads
  - AI and Analysis

## Setup

1. Copy `.env.example` to `.env`
2. Update environment variables with your:
   - Tailscale credentials
   - Weather API key
   - Location coordinates
   - GitHub username

## Configuration Files

- `services.yaml` - Service links and groupings
- `widgets.yaml` - Dashboard widget configuration
- `settings.yaml` - Core dashboard settings
- `bookmarks.yaml` - Quick access bookmarks
- `custom.css` - Visual customizations

## Requirements

- Docker environment
- Tailscale network
- WeatherAPI key
