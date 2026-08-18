# VideoQual

Video quality measurement for video engineers: calculate VMAF, PSNR, SSIM,
XPSNR, SSIMULACRA2, Butteraugli, and ColorVideo VDP across test encodes,
compare them with frame-exact A/B playback, and inspect bitrate independently.

More documentation is on its way as the project takes shape. For now:

- Requires Windows 10/11 and Python 3.11+ to run from source.
- FFmpeg 9+ with libvmaf must be available on `PATH`.
- Run with `python -m videoqual.main` after installing `requirements.txt`.

Licensed under the [MIT License](LICENSE). Copyright (c) 2026 Rithwik Reddy Eedula.
