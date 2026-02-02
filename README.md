<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bite Safe Privacy Policy</title>
    <style>
      :root {
        color-scheme: light;
        --bg: #ffffff;
        --fg: #111111;
        --muted: #555555;
        --border: #e5e5e5;
        --link: #0b66c3;
      }
      body {
        margin: 0;
        background: var(--bg);
        color: var(--fg);
        font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
        line-height: 1.55;
      }
      main {
        max-width: 860px;
        margin: 0 auto;
        padding: 40px 20px 64px;
      }
      h1 {
        font-size: 2rem;
        margin: 0 0 8px;
      }
      h2 {
        font-size: 1.25rem;
        margin: 28px 0 8px;
      }
      p {
        margin: 0 0 12px;
      }
      ul {
        margin: 0 0 12px 20px;
        padding: 0;
      }
      .muted {
        color: var(--muted);
      }
      hr {
        border: 0;
        border-top: 1px solid var(--border);
        margin: 24px 0;
      }
      a {
        color: var(--link);
      }
    </style>
  </head>
  <body>
    <main>
      <h1>Privacy Policy (Bite Safe)</h1>
      <p class="muted">Last updated: February 1, 2026</p>

      <h2>Overview</h2>
      <p>
        Bite Safe ("we," "our," "us") is a privacy-first application designed to operate
        entirely on your device. Bite Safe does not use accounts, does not operate backend
        servers, and does not collect, transmit, or store personal data outside your device.
      </p>

      <h2>Data Used On Device</h2>
      <ul>
        <li><strong>User-entered data:</strong> Ingredient trigger lists you manually enter.</li>
        <li><strong>Scanned text:</strong> Text recognized from ingredient labels using on-device OCR.</li>
        <li><strong>App data:</strong> Your trigger lists and settings stored locally in a SQLite database.</li>
      </ul>
      <p>
        This data never leaves your device unless you explicitly choose to share or export it.
      </p>

      <h2>Data We Do Not Collect</h2>
      <p>
        Bite Safe does not collect, transmit, or store:
      </p>
      <ul>
        <li>Personal identifiers (name, email address, phone number)</li>
        <li>Location data</li>
        <li>Usage analytics or telemetry</li>
        <li>Advertising or tracking data</li>
        <li>Crash or diagnostic reports linked to you</li>
        <li>Any data on external servers</li>
      </ul>

      <h2>Third-Party Libraries</h2>
      <p>
        Bite Safe uses third-party libraries to provide core functionality such as OCR,
        image selection, and sharing. All third-party libraries are configured for
        on-device use only, and Bite Safe does not send your data to third-party servers.
      </p>
      <p>
        Any data handling by third-party providers is governed by their respective privacy
        policies and by your device’s operating system settings.
      </p>

      <h2>Third-Party SDKs Used</h2>
      <ul>
        <li>Google ML Kit Text Recognition (<code>google_mlkit_text_recognition</code>)</li>
        <li>Image Picker (<code>image_picker</code>)</li>
        <li>Mobile Scanner (<code>mobile_scanner</code>)</li>
        <li>Device Info Plus (<code>device_info_plus</code>)</li>
        <li>Share Plus (<code>share_plus</code>)</li>
        <li>File Picker (<code>file_picker</code>)</li>
      </ul>

      <h2>Sharing and Exporting</h2>
      <p>
        You may optionally export your data as a base64-encoded file for backup or restore.
        You may also share your ingredient trigger list with another user by generating a
        QR code and having them scan it.
      </p>
      <p>
        These actions are entirely user-initiated. Bite Safe does not receive, store, or
        transmit this data.
      </p>

      <h2>Permissions</h2>
      <ul>
        <li><strong>Camera (optional):</strong> Used only to scan ingredient labels or QR codes.</li>
        <li><strong>Photos (optional):</strong> Used only if you choose to select an image for scanning.</li>
      </ul>
      <p>
        You can manage or revoke these permissions at any time in your device settings.
      </p>

      <h2>Data Retention</h2>
      <p>
        All app data remains on your device until you delete it within the app or uninstall Bite Safe.
      </p>

      <h2>Children’s Privacy</h2>
      <p>
        Bite Safe is not directed to children under the age of 13. Because the app does not
        collect data or use accounts, we have no means of identifying users’ ages.
      </p>

      <h2>Changes to This Policy</h2>
      <p>
        If this policy is updated, the “Last updated” date will be revised.
      </p>

      <hr>

      <h2>Contact</h2>
      <p>Justin Locke</p>
      <p><a href="mailto:jlocke926@gmail.com">jlocke926@gmail.com</a></p>
    </main>
  </body>
</html>
