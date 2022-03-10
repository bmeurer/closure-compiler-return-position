# Repro for weird return position in Closure compiled sourcemaps

```
npm install
npm run build
npm start
```

Open http://localhost:3000 in Chromium, open DevTools, reload the
page, and step once. It'll take you to the opening `}` of the
function.
