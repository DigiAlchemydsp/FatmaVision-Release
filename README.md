# FatmaVision

Watch your handheld's screen on your Windows PC over wifi, with minimal latency.

## Supported platforms

Knulli, Batocera, ArkOS, AmberELEC, ROCKNIX, muOS, and any Linux handheld
with SSH, ffmpeg (H.264 encoder) and a framebuffer display.

## How to use

1. Download and run `FatmaVision.exe`, no installation.
2. Click **Set Up Device**, pick your device OS (prefills the SSH login), enter
   the device IP, press **Set Up Device & Start Stream**, then **Done**.
   The app probes the device over SSH, prepares the stream scripts and
   launches them; all from the exe, you never touch the device.
3. Click **Connect** to watch the screen. Connect also re-starts the stream
   automatically; **Disconnect** stops it.
4. **Start Recording** saves `.mkv` files to `Captures\` next to the exe.
5. Press **F** for a fullscreen view.

Key auth works out of the box (Knulli, Batocera, AmberELEC, ROCKNIX); password
auth needs PuTTY `plink.exe` on PATH (ArkOS: ark/ark, muOS: root/muos).

SHA256 of FatmaVision.exe: AA7495643ADA7914737B86F67729968DCD1BE0143AE48D4985A53C19D97FE533
