# Third-party notices

This project bundles the following third-party JavaScript libraries. They are
inlined in `index.html` for offline / single-file usage. Their original
copyright and license notices are preserved in the source.

---

## lamejs 1.2.1

- **Purpose in this project:** MP3 encoding for the "导出音频 → MP3" feature.
- **License:** GNU Lesser General Public License v3.0 (LGPL-3.0).
- **Upstream:** <https://github.com/zhuker/lamejs>
- **Notice as included in the source:**

  ```
  /* lamejs 1.2.1 - MP3 encoder - LGPL-3.0 - https://github.com/zhuker/lamejs */
  ```

lamejs is a JavaScript port of the LAME MP3 encoder. LAME itself is
distributed under the GNU LGPL; the lamejs project distributes its code under
LGPL-3.0. The LGPL-3.0 license text is included in
[`licenses/LGPL-3.0.txt`](licenses/LGPL-3.0.txt). Because LGPL-3.0 is defined
as additional permissions on top of GPL-3.0, the GPL-3.0 text is also included
in [`licenses/GPL-3.0.txt`](licenses/GPL-3.0.txt).

## SoundTouch JS 0.3.0

- **Purpose in this project:** time-stretching / pitch-preserving playback
  speed (0.5x, 0.75x, 1x) and tempo-adjusted audio export.
- **License:** GNU Lesser General Public License v2.1 or later
  (LGPL-2.1-or-later).
- **Upstream:** <https://github.com/cutterbl/SoundTouchJS>
  (a JavaScript port of SoundTouch by Olli Parviainen).
- **Notice as included in the source:**

  ```
  /*
   * SoundTouch JS v0.3.0 audio processing library
   * Copyright (c) Olli Parviainen
   * Copyright (c) Ryan Berdeen
   * Copyright (c) Jakub Fiala
   * Copyright (c) Steve 'Cutter' Blades
   *
   * This library is free software; you can redistribute it and/or
   * modify it under the terms of the GNU Lesser General Public
   * License as published by the Free Software Foundation; either
   * version 2.1 of the License, or (at your option) any later version.
   * ...
   */
  ```

The LGPL-2.1 license text is included in
[`licenses/LGPL-2.1.txt`](licenses/LGPL-2.1.txt).

---

## Compliance notes

- The complete source of this application, including the bundled library code,
  is published in this repository (`index.html`), so the corresponding source
  of the LGPL components is available.
- If you redistribute this application, keep these notices, the license files
  and the upstream attribution intact.
- If you prefer a stricter separation, you can move the two `<script>` blocks
  containing lamejs and SoundTouch JS into separate `vendor/` files and load
  them with `<script src="...">` — the application logic will work the same.
