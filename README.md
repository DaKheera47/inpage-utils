# Urdu InPage Utils

Client-side web utilities for Urdu text conversion and PDF watermarking.

## Apps
- `index.html`: Unicode to InPage and InPage to Unicode converter
- `pdf-watermarker.html`: PDF watermarker
- `stripper.html`: HTML tag stripper

## Local Usage
Open any of the HTML files directly in a modern browser.

## Docker
Build the image:

```bash
docker build -t inpage-utils .
```

Run it on port `8055`:

```bash
docker run --rm -p 8055:8055 inpage-utils
```

Then open:
- `http://localhost:8055/` for the PDF watermarker
- `http://localhost:8055/index.html` for the converter
- `http://localhost:8055/stripper.html` for the HTML stripper

## License
MIT
