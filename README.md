# Upscaling One Axis: What Anisotropic Scale Actually Costs

The +2.2 dB for upscaling one axis instead of two was measured with twice the source pixels. Re-run at equal pixels it reverses: two-axis wins by 4.3 dB on isotropic content, one-axis wins by 16 dB when detail sits on the other axis. Plus a 1440x1080 to 1920x1080 test of pad, crop and stretch, and why nearest is the most expensive kernel.

**Read it with the tables and the reproduction snippets:** <https://celticgemini001.github.io/upgolab-anisotropic-upscale/>

## About this repo

This repository exists to serve one measured article. Every number in it came from
ffmpeg and numpy run on real files on this machine — the commands are in the page so
you can re-run them and get the same rows. Where the measurement contradicted the
hypothesis, the page says so.

## The tool behind the notes

<https://upgolab.com> — browser-based AI upscaler for photos and short video.

## Index

All the guides are cross-linked from the hub:
<https://celticgemini001.github.io/upgolab-tools/>
