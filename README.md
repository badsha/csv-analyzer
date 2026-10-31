# CSV Analyzer for Android

Two tools in one app:

- **Locate** finds the coordinates in a message and opens Google Maps directions to them. Works offline.
- **Analyze** signs in to your team's CSV Analyzer server so you can upload CSV or XLSX exports and explore activity, places on a map, contacts and devices.

## Download

Get the latest APK from the [Releases page](../../releases/latest).

## Install

1. On the phone, open the Releases page and tap the latest `csv-analyzer-<version>.apk`.
2. When Android asks, allow your browser to **install unknown apps**.
3. Tap **Install**. If Play Protect warns about an unknown developer, choose **Install anyway**.

Already have an older version? Install the new APK over it; there is no need to uninstall first.

Requires Android 8.0 or newer.

## Use

### Locate

- **Select text:** in any app, select the message with the coordinates, open the menu (⋮) and tap **Navigate to location**.
- **Share:** share the message to **CSV Analyzer**.
- **Paste:** copy the message, open CSV Analyzer and tap **Paste from clipboard**.

Check the location on the confirmation screen, then tap **Navigate**. Google Maps opens with directions from your current location. If Google Maps is not installed, another maps app or the browser is used.

### Analyze

1. Open the **Analyze** tab and sign in with the server address (it must start with `https://`), username and password your team gave you.
2. Upload a CSV or XLSX file, or load the demo data. If the columns are not recognised, match them in the form shown.
3. Optionally add a tower list (tower IDs with coordinates) to place towers on the map.
4. Open the dashboard: overview, activity charts, map with movement playback, locations, contacts, link graph, flags, devices and a searchable event log. Use the filter button to narrow by date, contact, type or tower.

Results are rule-based inferences, not proof.

## Privacy

- **Locate** works offline and sends nothing anywhere.
- **Analyze** connects only to the server address you enter, over HTTPS. Uploaded data stays in that server's memory for your session and is deleted when you sign out, delete it, or the session expires.
- The only thing saved on the phone is the last server address. Passwords, sessions and data are never stored, and map tiles are not cached.
- The map downloads tiles from the map provider your server is set up with (for example OpenStreetMap), which sees the areas you view.
- Screenshots of the app are blocked.
- Opening a maps app from Locate shares the destination with that app's provider.

## Verify the download (optional)

SHA-256 of `csv-analyzer-0.2.0.apk`:

```
4f53796f17aa874fdc30f666f1dfd49948f58a180f75dc88568bfc021afe3a6e
```
