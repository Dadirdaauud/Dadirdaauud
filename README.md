function getScreenshot(url) {
  const apiKey = '{your-key}';
  const base = 'https://app.link-snap.com/api/screenshot';
  const result = `${base}?key=${apiKey}&url=${url}&width=1600`;
  return result;
}
