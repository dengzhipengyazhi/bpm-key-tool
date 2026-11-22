# Security policy

## Scope

This is a **static, client-side web application**. It has no backend, no
server-side code, no database and no network communication:

- All audio processing happens locally in the browser (Web Audio API).
- The page loads no third-party scripts, fonts, analytics or CDNs.
- The only resource request other than `index.html` itself is the bundled
  `demo.wav` (same directory).
- No cookies, localStorage, IndexedDB, credentials or personal data.

## Reporting a vulnerability

If you find a security issue (for example XSS via file names/metadata, or a way
to make the app exfiltrate data), please **do not open a public issue**.
Use GitHub's private vulnerability reporting:

<https://github.com/dengzhipengyazhi/bpm-key-tool/security/advisories/new>

Please include the browser/OS, steps to reproduce, and the affected file/line.
