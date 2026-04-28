# Zen content (v0.2 internal beta)

Static manifests + assets served via GitHub Pages for the [Zen](https://huntersjq.github.io/zen-content/) iOS app.

Base URL: `https://huntersjq.github.io/zen-content/`

## Layout

```
zen-content/
├── zh/manifest.json
├── zh/<YYYY-MM-DD>/image.jpg
├── en-US/manifest.json
├── en-US/<YYYY-MM-DD>/image.jpg
└── _shared/<track>.m4a
```

Manifests follow the [v2 schema](https://huntersjq.github.io/zen-content/zh/manifest.json) — `withdrawn_dates`, optional `image_sha256` / `audio_sha256`.

## Adding / withdrawing content

See [the publishing guide in the app repo](https://github.com/huntersjq/Zen/blob/main/docs/CONTENT_PUBLISHING.md).

## Credits

- Images: Unsplash (CC0). Per-work attribution in each manifest's `image_credit` field.
- Audio: Internet Archive ambient field recordings (public domain). Per-work attribution in `audio_credit`.

## License

The manifest schema and structural code are MIT. Image and audio assets retain their original licenses (see `image_credit` / `audio_credit` in each manifest).
