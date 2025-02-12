---
title: Customizing colors in Files
---

Files comes with a large collection of custom background colors but additional customization is available for advanced users.

## Advanced themeing
To access theme values that are not exposed in the settings modal
1. Open Files > Settings > About > Open log location. This will open the app data folder for Files.
2. Open the `settings` folder and open the `user_settings.json` file. It's a good idea to close Files while modifying the settings file.

### Available resources for themeing

| Key                                   | Example                       | Default value                                |
| ------------------------------------- | ------------------------------| -------------------------------------------- |
| `AppThemeBackgroundColor`             | `#221d28`                     | `#00000000`                                  |
| `AppThemeAddressBarBackgroundColor`   | `#38343c`                     | `#00000000`                                  |
| `AppThemeSidebarBackgroundColor`      | `#464449`                     | `#00000000`                                  |
| `AppThemeFileAreaBackgroundColor`     | `#221d28`                     | `#00000000`                                  |
| `AppThemeFontFamily`                  | `Times New Roman`             | `Segoe UI Variable`                          |
