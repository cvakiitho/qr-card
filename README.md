# QR Card

[QR Card](https://cvakiitho.github.io/qr-card)

mobile first, extremely simple UI, saving state to query param, works offline.

### Implementation

- qr format spec: [https://qr-platba.cz/pro-vyvojare/specifikace-formatu/](https://qr-platba.cz/pro-vyvojare/specifikace-formatu/)
- qr generating library [https://www.npmjs.com/package/qrcode-generator](https://www.npmjs.com/package/qrcode-generator)
- single html file

### Notes

There are already some existing web apps for qr generation, but they are not very mobile friendly, and also usually make some api calls.

I don't think this should be used for anything serious.

Only for CZK to keep the UI simple.

Open source [https://github.com/cvakiitho/qr-card](https://github.com/cvakiitho/qr-card)

No Analytics, actually no external http calls.
