# Formward

**A form backend hosted in Sweden.** Point any HTML form at one endpoint and get submissions, spam filtering, email notifications, webhooks and exports, without running a server of your own.

Formward is built and operated from Stockholm, Sweden. Submissions are stored and processed in the EU; the sub-processor list, the Data Processing Agreement and the transfer-impact statement are public at [formward.eu/compliance](https://formward.eu/compliance), and the legal notice at [formward.eu/impressum](https://formward.eu/impressum).

## Start here

| | |
|---|---|
| Product | [formward.eu](https://formward.eu) |
| Docs | [formward.eu/docs](https://formward.eu/docs) (plain HTML, AJAX, webhooks, API, file uploads) |
| Framework examples | [formward.eu/frameworks](https://formward.eu/frameworks) (HTML, React, Next.js, Vue, Svelte, Astro, Framer, WordPress and more) |
| Site-builder guides | [formward.eu/guides](https://formward.eu/guides) |
| Form templates | [formward.eu/library](https://formward.eu/library) |
| Status | [formward.eu/status](https://formward.eu/status) |
| For AI agents | [formward.eu/llms.txt](https://formward.eu/llms.txt) |

The smallest possible integration:

```html
<form action="https://forms.formward.eu/f/YOUR_FORM_ID" method="POST">
  <input type="email" name="email" required />
  <textarea name="message" required></textarea>
  <input type="text" name="_gotcha" tabindex="-1" autocomplete="off" style="display:none" aria-hidden="true" />
  <button type="submit">Send</button>
</form>
```

## Repositories

| Repository | What it is |
|---|---|
| [n8n-nodes-formward](https://github.com/Formward/n8n-nodes-formward) | n8n community node: trigger on new submissions, read forms and submissions through the REST API |
| [formward-wordpress](https://github.com/Formward/formward-wordpress) | WordPress plugin "Formward Forms": a shortcode that renders an EU-hosted contact form |
| [formbutton](https://github.com/Formward/formbutton) | One script tag that adds a floating contact button and popup form to any site |
| [sdk-typescript](https://github.com/Formward/sdk-typescript) | Zero-dependency TypeScript client for the Formward REST API |

The product itself (dashboard, ingestion, worker) is not open source.

## Contact

Support: support@formward.eu. Security reports: security@formward.eu, see [formward.eu/security](https://formward.eu/security). Privacy and data protection: privacy@formward.eu.
