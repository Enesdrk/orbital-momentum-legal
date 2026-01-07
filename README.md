# Orbital Momentum - Legal Pages

This repository hosts the legal pages for the Orbital Momentum mobile game.

## Pages

- **[Home](https://YOUR-USERNAME.github.io/orbital-momentum-legal/)** - Landing page
- **[Privacy Policy](https://YOUR-USERNAME.github.io/orbital-momentum-legal/privacy.html)** - Our privacy policy
- **[Terms of Service](https://YOUR-USERNAME.github.io/orbital-momentum-legal/terms.html)** - Terms of service

## Setup

1. Create a new GitHub repository named `orbital-momentum-legal`
2. Upload all files from this folder to the repository
3. Go to **Settings** → **Pages**
4. Under **Source**, select `main` branch and `/ (root)` folder
5. Click **Save**
6. Your site will be live at `https://YOUR-USERNAME.github.io/orbital-momentum-legal/`

## Updating the App

After deploying, update the URLs in your Flutter app:

```dart
// lib/screens/settings_screen.dart

// Find these lines and update with your actual URLs:
() => _launchUrl('https://YOUR-USERNAME.github.io/orbital-momentum-legal/privacy.html'),
() => _launchUrl('https://YOUR-USERNAME.github.io/orbital-momentum-legal/terms.html'),
```

## Files

```
├── index.html      # Landing page
├── privacy.html    # Privacy Policy
├── terms.html      # Terms of Service
└── README.md       # This file
```

## License

© 2026 Orbital Momentum. All rights reserved.
