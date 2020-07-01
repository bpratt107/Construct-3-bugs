---
name: New bug report
about: Use this option to report a bug. You must use this option for your report to
  be investigated.
title: 'TileMap Consistent Crash '
labels: 'Tilemap'
assignees: ''

---

<!-- You must use this template or your issue will be closed without investigation. Please see the guidelines. -->

## Problem description

Game consistently crashes when selecting the "rectangle" tool in Tilemap. 

## Attach a .c3p

N/A

## Steps to reproduce

<!-- These steps are essential for us to be able to help you. Usually it is impossible to investigate reports unless they include steps we can follow ourselves, so please do your best to provide specific steps. There is no need to explain how you made the attached project - just explain what to do to with the project to observe the issue. -->

1. Open Tilemap editor with a png file. 
2. click on the "rectangle selection" area tool
3. Crash

## Observed result

<!-- What do you see happen? -->

## Expected result

should be able to use the area rectangle tilemap tool. 

## More details
<!-- Providing this information will make it more likely the issue you are reporting can be fixed quickly. -->

<!-- It's helpful to test as many browsers, platforms or export options as possible. For example an issue occurs in an Android app, does it also occur in Chrome on Windows? How about Firefox? etc. -->

**Affected browsers/platforms:** <!-- Chrome/Firefox/Safari, Windows/macOS/Android, etc -->

<!-- Identifying the first version the issue started happening can help resolve the issue more quickly. -->

**First affected release:** <!-- e.g. worked in r122 but broke in r123 -->

## System details

<!-- If you see a crash report dialog, please copy and paste it to where it says "PASTE HERE" below. -->
<!-- Otherwise please go to Menu > About > Platform information and paste that information there instead. -->

<details><summary>View details</summary>

Error report information
Type: unhandled exception
File: https://editor.construct.net/r204-2/components/bars/tilemapBar/tilemapBar.js, line 1, col 47460
Message: Uncaught TypeError: Cannot read property 'addEventListener' of null
Stack: TypeError: Cannot read property 'addEventListener' of null at window.ǃ$H.ǃekB.ǃeYN (https://editor.construct.net/r204-2/components/bars/tilemapBar/tilemapBar.js:1:47460) at window.ǃ$H.ǃekB.ǃecq (https://editor.construct.net/r204-2/components/bars/tilemapBar/tilemapBar.js:1:46600) at a.window.ǃ$H.ǃect (https://editor.construct.net/r204-2/components/bars/tilemapBar/tilemapBar.js:1:11479) at e.Event.ǃxNi.ǃxNu (https://editor.construct.net/r204-2/main.js:2:200145) at t.ǃkU.ǃHc.dispatchEvent (https://editor.construct.net/r204-2/main.js:2:197753) at e.ǃkU.ǃVh.ǃXDB.ǃIG.ǃXMP (https://editor.construct.net/r204-2/main.js:2:539367) at e.ǃkU.ǃVh.ǃXDB.ǃIG.ǃXM$ (https://editor.construct.net/r204-2/main.js:2:538637) at e.ǃkU.ǃVh.ǃXDB.ǃIG.ǃXMF (https://editor.construct.net/r204-2/main.js:2:538964) at ǃXMi (https://editor.construct.net/r204-2/main.js:2:534838)
Construct 3 version: r204.2
URL: https://editor.construct.net/
Date: Wed Jul 01 2020 15:23:47 GMT+0900 (Korean Standard Time)
Uptime: 115.5 s

Platform information
Browser: Chrome
Browser version: 83.0.4103.116
Browser engine: Chromium
Browser architecture: (unknown)
Context: browser
Operating system: Mac OS X
Operating system version: 10.15_5
Operating system architecture: (unknown)
Device type: desktop
Device pixel ratio: 1
Logical CPU cores: 4
Approx. device memory: 8 GB
User agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_5) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.116 Safari/537.36
C3 release: r204.2 (stable)
Language setting: en-US

WebGL information
Version string: WebGL 2.0 (OpenGL ES 3.0 Chromium)
Numeric version: 2
Supports NPOT textures: yes
Supports GPU profiling: yes
Supports highp precision: yes
Vendor: Intel Inc.
Renderer: Intel(R) HD Graphics 6000
Major performance caveat: no
Maximum texture size: 16384
Point size range: 1 to 255.875
Extensions: EXT_color_buffer_float, EXT_disjoint_timer_query_webgl2, EXT_float_blend, EXT_texture_compression_rgtc, EXT_texture_filter_anisotropic, OES_texture_float_linear, WEBGL_compressed_texture_s3tc, WEBGL_compressed_texture_s3tc_srgb, WEBGL_debug_renderer_info, WEBGL_debug_shaders, WEBGL_lose_context

</details>
