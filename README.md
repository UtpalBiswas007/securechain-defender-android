# Cyrax

This repository contains a personal Android app project for Cyrax, a blockchain and cybersecurity dashboard with a futuristic Windows-like interface.

## Overview

Cyrax is designed as an Android app built with Kotlin and Jetpack Compose. It includes placeholders and architecture for:

- Gmail / Google Account verification
- Real-time location tracking
- Blockchain wallet/watchlist monitoring
- AI-powered assistant chat
- VirusTotal or security scan integration
- Downloadable security reports
- Futuristic smooth UI inspired by Windows desktop aesthetics

## Current status

This project is in a working app scaffold state. Real API keys and platform credentials still need to be added for live functionality.

## Tech stack

- Kotlin
- Jetpack Compose
- Hilt
- Room
- Retrofit
- Encrypted local storage
- Coroutines + Flow

## Setup

1. Open the project in Android Studio.
2. Ensure Android SDK 34 is installed.
3. Add your API keys in a secure local config or secrets file.
4. Build and run the app.

## Important notes

- GPS access must be user-consented.
- Background location tracking requires Android policies and explicit opt-in.
- Threat scanning must use user-approved file or URL submission.
- Private keys and security data should remain encrypted and local-only unless the user explicitly chooses to export them.
