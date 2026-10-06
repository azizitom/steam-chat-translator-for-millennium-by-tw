# Steam Chat Translator for Millennium

Steam Chat Translator for Millennium is a plugin for the Windows Steam client running [Millennium](https://docs.steambrew.app/). It translates incoming Steam chat messages and prepares outgoing translations through Google Cloud Translation.

## Features

- Select source and target languages for outgoing translations.
- Preview the outgoing translation before inserting it into Steam's message field.
- Send the final message with Steam's normal send button.
- Configure incoming-translation language and visibility for a chat through the eye icon.
- Display only the translated message content; chat timestamps are excluded.

## Requirements

- Steam for Windows
- [Millennium](https://docs.steambrew.app/users/getting-started/installation)
- Google Cloud project with billing enabled
- Cloud Translation API enabled
- Google Cloud Translation API key

> This plugin uses **Google Cloud Translation API**, not Google Maps API.

## Install

1. Install Millennium using its [official Windows installation guide](https://docs.steambrew.app/users/getting-started/installation).
2. Download the latest `Steam Chat Translator for Millennium.zip` from the repository releases.
3. Extract the archive.
4. In Steam, open **Steam > Millennium > Plugins**.
5. Choose **Install plugin** and select `Steam Chat Translator for Millennium.star`.
6. Enable the plugin, open its menu, and choose **Restart**.
7. Open plugin configuration and paste a Google Cloud Translation API key.

## Google Cloud Translation API key

1. Open [Google Cloud Console](https://console.cloud.google.com/).
2. Create or select a project and enable billing.
3. Enable [Cloud Translation API](https://console.cloud.google.com/apis/library/translate.googleapis.com).
4. Open [Credentials](https://console.cloud.google.com/apis/credentials).
5. Choose **Create credentials > API key**.
6. Restrict the key to Cloud Translation API and paste it into the plugin configuration.

See Google's official [Cloud Translation setup guide](https://cloud.google.com/translate/docs/setup) and [API key guidance](https://cloud.google.com/docs/authentication/api-keys).

## Security

Do not commit or publish an API key. Restrict the key to Cloud Translation API and monitor Google Cloud usage and costs.
