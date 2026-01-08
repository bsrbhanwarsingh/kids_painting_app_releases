# releases/

This folder contains versioned APK releases for GitHub-based distribution.

## Structure

```
releases/
├── app-1.0.37.apk
├── app-1.0.38.apk
└── app-1.0.39.apk (latest)
```

## Automatic Management

The `publish_update.bat` script:
- Automatically saves new releases here
- Keeps only the last 2 versions
- Updates `version.json` with latest release URL

## Distribution

APKs are accessible via GitHub raw URLs:
```
https://github.com/bsrbhanwarsingh/kids_painting_app_Copy/raw/master/releases/app-1.0.39.apk
```

This folder is tracked in Git for automatic update distribution.
