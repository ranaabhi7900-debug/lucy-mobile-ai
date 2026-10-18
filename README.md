# Lucy Mobile UI

Mobile-first single-page Lucy companion UI with CSS 3D avatar animation, responsive chat bubbles, quick prompts, and Hindi browser voice fallback.

## GitHub Pages

The included workflow deploys `index.html` automatically on every push to `main`.

## Backend connection

GitHub Pages is static and must not contain Groq, Sarvam, or Hugging Face secrets. To connect the FastAPI backend, open the page with:

```text
https://YOUR-USERNAME.github.io/YOUR-REPO/?api=https://YOUR-BACKEND.example.com
```

Without `?api=...`, the UI works in demo mode and uses the browser's Hindi speech synthesis fallback.
