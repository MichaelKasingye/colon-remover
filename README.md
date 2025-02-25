# Colon Remover

A lightweight web utility that removes colons from formatted strings like MAC addresses, certificate fingerprints, and other colon-delimited identifiers.

## Features

- **Simple Interface**: Clean, user-friendly design for quick operation
- **Instant Processing**: Removes colons from input text in real-time
- **Copy to Clipboard**: One-click copying of processed results
- **Responsive Design**: Works on desktop and mobile devices
- **No Server Dependencies**: Runs entirely in the browser with no backend required

## Use Cases

- Remove colons from MAC addresses
- Clean up certificate fingerprints
- Format hardware identifiers
- Remove delimiters from any colon-separated string

## Example

**Input:**
```
48:33:21:6B:A3:7C:D3:DC:05:68:35:A6:84:7A:5F:30:44:BC:22:AE
```

**Output:**
```
483321A37CD3DC056835A6847A5F3044BC22AE
```


## How It Works

The utility uses JavaScript to:
1. Capture user input from the text field
2. Apply a regular expression to remove all colons: `input.replace(/:/g, '')`
3. Display the processed result
4. Provide a copy-to-clipboard function for convenience

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## Acknowledgments

- Built with vanilla HTML, CSS, and JavaScript
- No external dependencies or libraries required

---

Made with ❤️ by [https://github.com/MichaelKasingye]
