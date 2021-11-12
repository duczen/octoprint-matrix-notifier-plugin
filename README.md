# Matrix Notifier for OctoPrint

Send messages and snapshots to matrix rooms.

## Setup

Install manually using this URL:

    https://github.com/duczen/octoprint-matrix-notifier-plugin/archive/main.zip

## Configuration

The plugin can be configured via the octoprint UI. You will need the room alias or room id of the matrix room as well as your server address and an access token.

The easiest way to obtain an access token is to login with Element, copy the access token from the settings panel and then *do not logout*.


### Making a Release

1. Update the version number in `setup.py`, push to `main`.
1. Check the release draft on GitHub, make sure version number matches the
   `setup.py`.
1. Publish Release on GitHub.
