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

SHA256 of FatmaVision.exe: 92C167DDA00252B611BA3D7A4538D9135DD08F19A6713F9B505297A978DCEF53
