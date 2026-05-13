# Embed Tools

A collection of lightweight, embeddable HTML tools.

## Tools

| Tool | Description | File |
|------|-------------|------|
| **Countdown** | A customizable countdown timer embed. Supports `title` and `date` URL parameters. | `countdown.html` |
| **Visitor Counter** | Tracks visits via Upstash Redis. Supports `title`, `label`, `name`, and `color` params. Auto-detects embedder domain. | `visitor-counter.html` |

## Usage

Open any tool directly in a browser, or embed it via `<iframe>`.

### Countdown Example

```html
<iframe
  src="countdown.html?title=My+Event&date=2026-12-31T23:59:59"
  width="100%"
  height="300"
  frameborder="0"
></iframe>
```

### Visitor Counter Example

```html
<iframe
  src="visitor-counter.html?title=Welcome%21&label=Page+Views&color=0ea5e9"
  width="100%"
  height="200"
  frameborder="0"
></iframe>
```

## License

MIT
