# @open-choice/web-ui

Shared design tokens and Astro components for the Open Choice marketing site (`openchoice.app`) and the plugin registry (`registry.openchoice.app`).

Consumed directly from git:

```json
{
  "dependencies": {
    "@open-choice/web-ui": "github:open-choice/web-ui#main"
  }
}
```

## What's in here

- `src/styles/tokens.css` — brand colors, spacing, typography shared by both sites.
- `src/styles/endpoint.css` — styling for endpoint help pages (parameters table, templates, code blocks).
- `src/components/SiteHeader.astro`, `SiteFooter.astro` — shared site chrome.
- `src/components/EndpointHelp.astro` — renders one endpoint's help JSON (title, usage, parameters, examples, notes) in the same structure as the app's endpoint-help-page panel.
- `src/components/ParametersTable.astro` — parameters table in isolation.
- `src/components/TemplateCard.astro` — one `.oce` template with copy-to-clipboard.

## Design target

Both consumer sites use Astro. This package ships only `.css` and `.astro` files. No build step.
