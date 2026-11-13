# WorldChanger map resources

Optional map packages for WorldChanger **2.6.8-beta.2 or later**.

In WorldChanger, open **Camera → Map cache**:

- Select a map and choose **Install map**.
- Choose **Download all maps** to install the full collection. The confirmation shows the map count and size before downloading.
- Use **Cancel installation** to stop. Completed files stay on disk and are reused on retry.

The collection contains **24 maps**, with approximately **3.88 GB** of compressed map data plus catalogs. Installed maps remain available offline. Existing verified files are reused.

GitHub is the default source when **Map resource source** is empty. Players do not need a GitHub account, token or GitHub CLI. Downloads start only after an explicit installation action.

Resources are available in the immutable [maps-v1 release](https://github.com/Zalupenok/worldchanger-maps/releases/tag/maps-v1). The `.chunks` files are used directly by WorldChanger; installation through the script handles integrity checks, caching and resumable downloads.
