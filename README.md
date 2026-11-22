# NEXUS — Where Intelligence Awakens

An original, self-contained scroll-driven visual experience. The artwork is generated procedurally in Canvas: a liquid point evolves into matter, a connected particle field, a compact consciousness core, and an abstract NEXUS sigil.

## Run locally

No build step or package installation is required.

```bash
python3 -m http.server 8000
```

Open http://localhost:8000

You can also open `index.html` directly in a modern browser. Internet access is only used for the optional Google Fonts import; the experience itself has no external JavaScript dependencies.

## Interaction

- Scroll to scrub the five states of the visual narrative.
- Move the pointer to subtly influence the field.
- Toggle the optional low-frequency ambient tone in the top-right corner.
- Use “Replay the awakening” in the footer to return to the beginning.

## Notes

- Responsive layout for desktop and mobile.
- Respects `prefers-reduced-motion`.
- Canvas rendering is capped at device pixel ratio 2 and particle count 1,250.
- The contact CTA currently uses a placeholder `hello@nexus.example`; replace it with a real address before publishing.
