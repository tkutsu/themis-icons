# Niagara Outline variants

These 923 vector icons were extracted from Niagara Launcher 1.16.34 (version code 1640, package `bitpit.launcher`) on the connected phone on 2026-11-01. The source APK's SHA-256 is `813e34b944a687d396ff76c8bbd69db718cd91d884429cc2a1d69dceb11687a2`.

The SVGs retain the Android vector path data. Android theme attributes are resolved to an unfilled outline with a 1-unit stroke, scale 1, round ends and joins where specified, and Themis's `#ececec` foreground. Weather palette colors use the same monochrome foreground. This is a fixed SVG rendering of the artwork, not an export of the phone's active theme settings.

## Folders and names

- `apps/16/` contains 583 app icons and 157 category icons. Themis's existing app size folders and `apps/scalable` link here. Its `categories` directory links to `apps`, so category variants are also available there.
- `actions/16/` contains 168 action icons.
- `status/16/` contains 15 weather icons.

All imported names end in `-niagara-outline.svg`. App names preserve the package identifier encoded in the source resource, with underscores changed to hyphens, for example `com-spotify-music-niagara-outline.svg`. Category names start with `category-`, for example `category-web-browser-niagara-outline.svg`. Action and weather names describe the drawing.

There are also 111 relative symlinks for common desktop names, such as `spotify-niagara-outline.svg`, `firefox-niagara-outline.svg`, `org.mozilla.firefox-niagara-outline.svg`, and `edit-copy-niagara-outline.svg`. Existing icons and aliases are preserved. The existing theme index already registers these folders as scalable.

`apps/16/regimen.svg` is a desktop adaptation of the food category drawing with a 1.5-unit stroke. It keeps the original path and avoids the padding of Regimen's former PNG. The original `category-food-niagara-outline.svg` is unchanged.

[niagara-outline.tsv](niagara-outline.tsv) maps every source Android resource to its SVG and lists each alias target. Use the filename without `.svg` when choosing an icon by theme name. For example, use `firefox-niagara-outline` in an application's icon setting.

## Source and rights

The artwork comes from [Niagara Launcher](https://niagaralauncher.app/) by Mellowdrop. Niagara documents the original styles in its [Anycons guide](https://help.niagaralauncher.app/article/149-anycons).

No separate artwork redistribution license was found with the extracted resources. Themis's `COPYING` does not establish a GPL license for these imported drawings, and this import claims no such grant. The source APK and private app data are not included.
