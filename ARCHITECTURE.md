# Architecture

## Main idea

A modular VPN client for Android and iOS that supports multiple protocols
through separate adapters.

## Protocol adapters

- AmneziaWG adapter
- Xray adapter
- Hysteria 2 adapter

## Shared app features

- Profile list
- Import by QR code
- Import by file
- Import by link
- Secure key storage
- Connection manager
- Logs screen
- Diagnostics screen

## Security rules

- Private keys are generated or imported on device
- Keys are stored only in platform secure storage
- No third-party analytics SDKs
- No traffic logging
