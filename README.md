# InkSight Starter — Web Reference Viewer

Minimal, zero-dependency proof-of-concept for the Meta Ray-Ban Display web-app path. Includes local reference image selection, zoom, pan, and keyboard navigation. The interface is designed around the 600×600 additive display. No AI or camera integration yet.

## Test locally
Open `index.html` in a desktop browser and select an image. Use +/− to zoom, drag to pan, or arrow keys to zoom. For device testing, host over HTTPS and follow Meta's Web Apps developer-mode instructions to add its URL in the Meta AI app. Test actual file selection, browser input mapping, and storage on device; these are not yet validated.

## Next steps
- Replace local file input with reference upload to a private backend or an accessible image library if device file selection isn't supported.
- Add Neural Band interaction mapping per current Meta docs.
- Implement a native iOS camera bridge using Meta CameraAccess sample.
- Add authenticated vision API calls from a backend, never expose API keys in the web app.
- Require deliberate capture and consent; do not upload client tattoo photos without authorization.

Official docs: https://developers.meta.com/wearables/web-apps/