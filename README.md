# Website Redirector

A modern, responsive web page that allows you to redirect to any desired website.

## Features

- **Instant Redirect**: Redirect immediately to any website
- **Delayed Redirect**: Redirect with a 5-second countdown
- **URL Validation**: Automatically validates and formats URLs
- **Quick Presets**: One-click redirects to popular websites
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient design with smooth animations

## How to Use

### Method 1: Manual Input
1. Open `index.html` in your web browser
2. Enter the website URL you want to redirect to
3. Click "🚀 Redirect Now" for immediate redirect
4. Or click "⏱️ Redirect in 5s" for a delayed redirect

### Method 2: Quick Presets
- Click any of the preset buttons (Google, GitHub, YouTube, etc.) for instant redirect

### Method 3: URL Parameter
- Add `?redirect=https://example.com` to the URL for automatic redirect
- Example: `index.html?redirect=https://www.google.com`

## URL Format Support

The redirector supports various URL formats:
- `https://example.com`
- `http://example.com`
- `example.com` (automatically adds https://)

## Browser Compatibility

Works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Local Development

To run locally:
1. Download the `index.html` file
2. Open it in any web browser
3. No server required - works offline!

## Security Note

This redirector uses client-side JavaScript and `window.location.href` for redirection. Some browsers may block redirects to certain websites for security reasons. 

const targetWebsite = "https://www.google.com"; 