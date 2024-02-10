 
# Laravel with Pusher Chat Demo

This is a chat application built with Laravel and Pusher. It demonstrates real-time messaging using Pusher's WebSocket technology.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- Real-time chat functionality
- Laravel backend with Pusher integration
- Simple and clean user interface

## Requirements
- PHP >= 8.1
- Laravel >= 10
- Composer
- Pusher account (API key, secret, and app ID)

## Installation
1. Install dependencies:
   ```bash
   cd laravel-push-chat-demo
   composer install
   ```

2. Copy the `.env.example` file to `.env`:

   ```bash
   cp .env.example .env
   ```

3. Configure your Pusher credentials in the `.env` file:

   ```dotenv
   BROADCAST_DRIVER=pusher
   PUSHER_APP_ID=your-app-id
   PUSHER_APP_KEY=your-app-key
   PUSHER_APP_SECRET=your-app-secret
   PUSHER_APP_CLUSTER=your-app-cluster
   ```

4. Run migrations and seed the database:

   ```bash
   php artisan migrate --seed
   ```

