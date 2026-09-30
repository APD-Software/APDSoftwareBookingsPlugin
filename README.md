# APDSoftware Bookings Plugin CDN

Public distribution assets for the APDSoftware bookings frontend plugin.
Built and published by the `Bookings Plugin CDN Publish` workflow in the private
[APD-Software/APDSoftware](https://github.com/APD-Software/APDSoftware) repository (`APDSoftware.Frontend.Bookings.Next`).
Do not edit `dist/` by hand; every publish overwrites it.

- Latest: `https://cdn.jsdelivr.net/gh/APD-Software/APDSoftwareBookingsPlugin@main/dist/bookings-plugin-loader.js`
- Pinned (use this on live sites): `https://cdn.jsdelivr.net/gh/APD-Software/APDSoftwareBookingsPlugin@v0.1.0/dist/bookings-plugin-loader.js`

```html
<div data-apdsoftware-bookings data-api-base-url="https://<your-host>/api"></div>
<script type="module" src="https://cdn.jsdelivr.net/gh/APD-Software/APDSoftwareBookingsPlugin@v0.1.0/dist/bookings-plugin-loader.js"></script>
```

Global API: `window.APDSoftwareBookingsPlugin` (`configure()`, `mount()`, `unmount()`, `autoMount()`, `open()`).
Full embed options: `APDSoftware.Frontend.Bookings.Next/README.md` in the private repository.
