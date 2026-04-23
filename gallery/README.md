# Gallery files

Drop your photos and videos here. Then update the `GALLERY_ITEMS` array in `index.html`.

## How to add items

In `index.html`, find `const GALLERY_ITEMS = [` and edit the list:

```js
const GALLERY_ITEMS = [
  { type: 'photo', src: 'gallery/photo_01.jpg', caption: 'Recording day!' },
  { type: 'video', src: 'gallery/video_01.mp4', caption: 'Reading practice' },
  // add as many as you like…
];
```

- **type**: `'photo'` or `'video'`
- **src**: path relative to `index.html` (always starts with `gallery/`)
- **caption**: shown in the thumbnail and lightbox (leave `''` to hide)

## Supported formats

| Type  | Formats                |
|-------|------------------------|
| Photo | `.jpg` `.jpeg` `.png` `.webp` |
| Video | `.mp4` `.mov` `.webm`  |

## Tips

- Square crops look best in the grid — portrait/landscape also work.
- Videos show a ▶ overlay in the grid and play inline in the lightbox.
- Order in the array = order in the grid.
