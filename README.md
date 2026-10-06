# Steam Chat Translator for Millennium by TW

Language translation plugin for the Windows Steam client, powered by Google Cloud Translation.

## Features

- Translate incoming Steam chat messages.
- Choose the source and target languages for outgoing translations.
- Preview an outgoing translation before inserting it into Steam’s message field.
- Send with Steam’s standard Send button.
- Configure incoming translation language and visibility using the eye icon in a chat.
- Chat timestamps are excluded from translated text.

## Installation

1. Install [Millennium](https://docs.steambrew.app/users/getting-started/installation) for Steam.
2. Download the plugin ZIP from the latest release.
3. Extract the archive.
4. In Steam, open **Steam > Millennium > Plugins**.
5. Select **Install plugin** and choose `Steam Chat Translator for Millennium by TW.star`.
6. Enable the plugin and select **Restart** from its menu.
7. Open plugin configuration and paste a Google Cloud Translation API key.

## Google API key

This plugin uses **Google Cloud Translation API**, not Google Maps API.

1. Open [Google Cloud Console](https://console.cloud.google.com/).
2. Create or select a project and enable billing.
3. Enable [Cloud Translation API](https://console.cloud.google.com/apis/library/translate.googleapis.com).
4. Open [Credentials](https://console.cloud.google.com/apis/credentials).
5. Select **Create credentials > API key**.
6. Restrict the key to Cloud Translation API and paste it into the plugin configuration.

See Google’s [Cloud Translation setup guide](https://cloud.google.com/translate/docs/setup) and [API key guidance](https://cloud.google.com/docs/authentication/api-keys).

## Downloads

- The plugin package is available in [Releases](../../releases).
- The source archive is included in this repository.

## Security

Do not share or publish your Google API key. Restrict it to Cloud Translation API and monitor usage and costs.
