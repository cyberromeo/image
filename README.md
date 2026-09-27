# image

Static image CDN for the Medx Elite PWA, served via jsDelivr:

```
https://cdn.jsdelivr.net/gh/cyberromeo/image@main/<path>
```

## optha-td/

Figures for the **Ophthalmology T & D** batch test. Content-addressed
(`optha-td/<sha1[:2]>/<sha1>.webp`): question clinical photos and rendered
answer/explanation slides. Filenames are the SHA-1 of the bytes, so identical
images dedupe and URLs never change.
