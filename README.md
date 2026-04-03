# Pinpoint Widget

Universal feedback widget for any website. One script tag, instant user feedback.

## 🚀 Quick Start

Add this single line to your website:

```html
<script src="https://cdn.jsdelivr.net/gh/enoob15/pinpoint-widget@latest/pinpoint.min.js" 
        data-project="your-project-api-key"></script>
```

Get your API key from: https://pinpoint.boone51.com

## ✨ Features

- **Visual Feedback Pins** - Users click any element, drop a pin, add a comment
- **Rage & Dead Clicks** - Detect frustration and confusion automatically
- **Error & Console Capture** - Uncaught errors with stack traces
- **Abandonment Tracking** - Know when and why users leave
- **Zero Dependencies** - Pure TypeScript, 40KB minified
- **Privacy First** - No cookies, no tracking scripts

## 🔧 Configuration

```html
<script 
  src="https://cdn.jsdelivr.net/gh/enoob15/pinpoint-widget@latest/pinpoint.min.js"
  data-project="your-api-key"
  data-endpoint="https://pinpoint.boone51.com/api/ingest"
  data-position="bottom-right"
  data-theme="dark"
></script>
```

### Options

- `data-project` (required) - Your project API key  
- `data-endpoint` - Custom ingest endpoint (defaults to Pinpoint SaaS)
- `data-position` - Button position: `bottom-right`, `bottom-left`, `top-right`, `top-left`
- `data-theme` - Theme: `light`, `dark`, `auto`
- `data-ignore-urls` - Comma-separated URLs to exclude from network monitoring

## 📊 What Gets Captured

### Active Feedback
- Pin screenshots with element selectors
- User comments and feedback text
- Full page context and viewport info

### Passive Telemetry  
- Console logs, warnings, and errors (last 50)
- Failed network requests (fetch/XHR)
- JavaScript errors with stack traces
- User behavior (scroll depth, idle time, rage clicks)
- Environment info (browser, OS, viewport, etc.)

## 🔐 Privacy & Security

- **No personal data** - We don't capture form inputs, auth tokens, or PII
- **Selective monitoring** - Exclude sensitive endpoints with `data-ignore-urls`
- **Shadow DOM isolation** - Widget can't break your site's CSS/JS
- **GDPR compliant** - No cookies or persistent tracking

## 🛠 Development

```bash
# Clone the source (for customization)
git clone https://github.com/enoob15/pinpoint-widget
cd pinpoint-widget

# Widget is distributed pre-built
# For source code and custom builds, see:
# https://github.com/enoob15/pinpoint-dashboard
```

## 📖 Documentation

- **Dashboard**: https://pinpoint.boone51.com
- **Pricing**: https://pinpoint.boone51.com/pricing  
- **API Docs**: https://github.com/enoob15/pinpoint-dashboard
- **Support**: hello@boone51.com

## 📄 License

MIT License - Use freely in commercial and personal projects.

---

**Built by Boone51 Studios** | **Powered by Pinpoint Analytics**