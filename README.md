# Widevine L3 Guesser Extension

## Installation

1. **Download or Clone**  
   Get a copy of this code by either downloading it or cloning it using Git.

2. **CDM Files**  
   In the same directory as `manifest.json` (the root directory of this extension), place one of the following Android L3 CDM files:
   - Supported CDM Types:
     1. `device.wvd`
     2. `device_client_id_blob` + `device_private_key`
     3. `client_id.bin` + `private_key.pem`

3. **Install Extension**

   - **Firefox**
     1. Go to `about:debugging#/runtime/this-firefox` in your Firefox browser.
     2. Load the extension as a temporary addon.

   - **Chrome**
     1. Navigate to `chrome://extensions/` in your Chrome browser.
     2. Load the extension as an unpacked extension.
