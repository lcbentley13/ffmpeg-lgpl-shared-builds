# About

This software uses libraries from the FFmpeg project (https://ffmpeg.org) licensed under the GNU Lesser General Public License version 2.1 (LGPLv2.1).

FFmpeg is a trademark of its respective owners.

**Platform:** %%Platform%%

**FFmpeg Version:** %%FFmpeg-Version%%

## License

FFmpeg is licensed under the LGPL v2.1. A copy of this license is provided in the file `LICENSE` included with this distribution.

## Source Code

The complete corresponding source code for the FFmpeg libraries used in this distribution is provided in the archive `%%Source-Code-Archive%%`.

This source code corresponds to the exact version used to build the distributed binaries.

No functional modifications have been made to the FFmpeg source code.

The source code is also available from the official FFmpeg project website:
https://ffmpeg.org

## Compilation

The FFmpeg libraries were compiled using the following configuration:

```
%%Compilation-Script%%
```

## Dynamic Linking

This application uses FFmpeg exclusively through **dynamic linking**. The FFmpeg shared libraries are located in the `/lib` directory.

Users may replace these libraries with compatible versions of FFmpeg, including modified versions, without affecting the rest of the application.

## User Rights (LGPL Compliance)

In accordance with the LGPL v2.1:

* You may modify the FFmpeg libraries and use your modified versions with this application.
* You may replace the FFmpeg shared libraries in the `/lib` directory with your own builds.
* You may reverse engineer this application **solely for the purpose of debugging modifications to the FFmpeg libraries**.

## No Warranty

FFmpeg is provided "as is" without warranty of any kind, as described in the LGPL v2.1 license.
