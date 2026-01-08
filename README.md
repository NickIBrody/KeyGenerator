# Telegram Activation Key System

A lightweight and reusable activation key system for Telegram bots built with aiogram.

This module allows bot owners to:
- generate one-time activation keys
- restrict access to bot features
- manage users via simple key-based activation
- store data locally using SQLite

## Features
- Admin-only key generation
- One-time activation keys
- SQLite database (no external services required)
- Easy integration into existing bots
- Minimal dependencies

## Use cases
- Paid access to Telegram bots
- Trial or subscription-based features
- Private or invite-only bots
- Licensing system for bot features

## Installation
Clone the repository and integrate the module into your bot project.

## Requirements
- Python 3.9+
- aiogram
- SQLite

## Notes
This project is designed as a modular component and can be easily extended
(e.g. time-limited keys, user binding, subscriptions).

## License
MIT

