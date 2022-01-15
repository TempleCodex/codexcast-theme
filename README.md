# owncast-theme
The theme for the temple codex streaming platform.

## How to use
You paste this in `{host-url}/admin/config-public-details/`

```css
/* ===== Hacked together CSS Start ===== */

/* ===== Initial Setup ===== */
:root {
    /* Enclave Colors */
    --enclave-chaos: #ad2d47;
    --enclave-mystery: #8e76b0;
    --enclave-logic: #226797;
    --enclave-structure: #01806c;
    --enclave-order: #bba96d;

    /* Temple Branding */
    --temple-black: #0C0B0B;
    --temple-brown: #BD7B4F;

    /* Owncast Overrides */
    --owncast-purple: var(--temple-brown) !important;
    --header-bg-color: var(--temple-black) !important;
}

/* ===== Initial End ===== */
/* ===== Body + Background Colors ===== */

body, [class*="bg-gray"] {
    background-color: var(--temple-black) !important;
}

/* Text Options */
.instance-title, [class*="text-indigo"] {
    color: var(--temple-brown);
}

[class*="text-gray"] {
    color: white !important;
}

/* ===== Body + Background Colors End ===== */
/* ===== Body ===== */
#stream-info {
    border: none;
}
/* ===== Body ===== */
/* ===== Images ===== */

.user-image {
    background-color: transparent !important;
}

#logo-container {
    background-image: url(/logo);
    background-color: transparent;
  /* This is active because our logo won't scale down well atm */ 
    /* display: none !important; */
}

#emoji-button {
    filter: grayscale(1) brightness(2);
}

/* ===== Images End ===== */
/* Hacked Together CSS End */
```
