---
title: "Social Networks"
variant: "socials"
---

<style>
  .social-grid {
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
    max-width: 28rem;
    margin: 0 auto;
  }
  .social-link {
    display: flex;
    align-items: center;
    gap: 0.875rem;
    padding: 0.75rem 1rem;
    border: 1px solid hsl(var(--border));
    border-radius: 0.5rem;
    text-decoration: none;
    color: hsl(var(--foreground));
    background: hsl(var(--card));
    transition: background 0.15s, border-color 0.15s;
  }
  .social-link:hover {
    background: hsl(var(--accent));
    border-color: hsl(var(--ring));
  }
  .social-link svg {
    width: 1.5rem;
    height: 1.5rem;
    flex-shrink: 0;
  }
  .social-link .label {
    font-weight: 500;
    font-size: 0.95rem;
  }
  .social-link .handle {
    margin-left: auto;
    font-size: 0.8rem;
    color: hsl(var(--muted-foreground));
    font-family: monospace;
  }
</style>

<div class="social-grid">

<a class="social-link" href="https://github.com/lbenicio" target="_blank" rel="noopener noreferrer">
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.5-.67 1.08-.82 1.7-.15.62-.2 1.27-.18 1.9V22"/></svg>
  <span class="label">GitHub</span>
  <span class="handle">lbenicio</span>
</a>

<a class="social-link" href="https://www.linkedin.com/in/leonardo-benicio" target="_blank" rel="noopener noreferrer">
  <svg viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452H17.21V14.86c0-1.333-.27-3.046-2.145-3.046-1.86 0-2.145 1.45-2.145 2.948v5.69H9.069V9h2.852v1.561h.044c.434-.82 1.494-1.686 3.074-1.686 3.29 0 3.897 2.165 3.897 4.983v6.594zM5.337 7.433a1.805 1.805 0 11-.002-3.61 1.805 1.805 0 01.002 3.61zM6.763 20.452H3.911V9h2.852v11.452z"/></svg>
  <span class="label">LinkedIn</span>
  <span class="handle">leonardo-benicio</span>
</a>

<a class="social-link" href="https://twitter.com/lbenicio_" target="_blank" rel="noopener noreferrer">
  <svg viewBox="0 0 24 24" fill="currentColor"><path d="M19.633 7.997c.013.177.013.354.013.53 0 5.386-4.099 11.599-11.6 11.599-2.31 0-4.457-.676-6.265-1.842.324.038.636.05.972.05 1.91 0 3.67-.65 5.07-1.755a4.099 4.099 0 01-3.827-2.84c.25.039.5.064.763.064.363 0 .726-.051 1.065-.139a4.091 4.091 0 01-3.282-4.015v-.051c.538.3 1.162.482 1.824.507a4.082 4.082 0 01-1.826-3.405c0-.751.2-1.435.551-2.034a11.63 11.63 0 008.44 4.281 4.615 4.615 0 01-.101-.938 4.091 4.091 0 017.078-2.799 8.1 8.1 0 002.595-.988 4.112 4.112 0 01-1.8 2.261 8.2 8.2 0 002.357-.638 8.824 8.824 0 01-2.047 2.115z"/></svg>
  <span class="label">Twitter / X</span>
  <span class="handle">lbenicio_</span>
</a>

<a class="social-link" href="https://mastodon.social/@lbenicio" target="_blank" rel="noopener noreferrer">
  <svg viewBox="0 0 24 24" fill="currentColor"><path d="M23.193 7.879c0-5.206-3.411-6.732-3.411-6.732C18.062.357 14.108.025 12.041 0h-.076c-2.068.025-6.02.357-7.74 1.147 0 0-3.411 1.526-3.411 6.732 0 1.192-.023 2.618.015 4.129.124 5.092.934 10.109 5.641 11.355 2.17.574 4.034.695 5.535.612 2.722-.15 4.25-.972 4.25-.972l-.09-1.975s-1.945.613-4.129.539c-2.165-.074-4.449-.233-4.799-2.891a5.499 5.499 0 0 1-.048-.745s2.125.52 4.817.643c1.646.075 3.19-.097 4.758-.283 3.007-.359 5.625-2.212 5.954-3.905.517-2.665.475-6.507.475-6.507zm-4.024 6.482h-2.507V9.129c0-1.308-.548-1.972-1.646-1.972-1.213 0-1.822.784-1.822 2.337v3.386H10.75V9.494c0-1.553-.609-2.337-1.822-2.337-1.098 0-1.646.664-1.646 1.972v5.232H4.775V8.9c0-1.289.328-2.313.987-3.069.68-.758 1.569-1.146 2.674-1.146 1.278 0 2.246.491 2.886 1.474L12 7.352l.678-1.193c.64-.983 1.608-1.474 2.886-1.474 1.104 0 1.994.388 2.674 1.146.658.756.987 1.78.987 3.069v5.461z"/></svg>
  <span class="label">Mastodon</span>
  <span class="handle">@lbenicio</span>
</a>

<a class="social-link" href="https://bsky.app/profile/lbenicio.bsky.social" target="_blank" rel="noopener noreferrer">
  <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 10.8c-1.087-2.114-4.046-6.053-6.798-7.995C2.566.944 1.561 1.266.902 1.565.139 1.908 0 3.08 0 3.768c0 .69.378 5.65.624 6.479.815 2.736 3.713 3.66 6.383 3.364.136-.02.275-.039.415-.056-.138.022-.276.04-.415.056-3.912.58-7.387 2.005-2.83 7.078 5.013 5.19 6.87-1.113 7.823-4.308.953 3.195 2.05 9.271 7.733 4.308 4.267-4.308 1.172-6.498-2.74-7.078a8.741 8.741 0 0 1-.415-.056c.14.017.279.036.415.056 2.67.297 5.568-.628 6.383-3.364.246-.828.624-5.79.624-6.478 0-.69-.139-1.861-.902-2.206-.659-.298-1.664-.62-4.3 1.24C16.046 4.748 13.087 8.687 12 10.8Z"/></svg>
  <span class="label">Bluesky</span>
  <span class="handle">lbenicio.bsky.social</span>
</a>

<a class="social-link" href="https://instagram.com/lbenicio_" target="_blank" rel="noopener noreferrer">
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"/><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"/><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"/></svg>
  <span class="label">Instagram</span>
  <span class="handle">lbenicio_</span>
</a>

<a class="social-link" href="https://youtube.com/@lbenicio" target="_blank" rel="noopener noreferrer">
  <svg viewBox="0 0 24 24" fill="currentColor"><path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/></svg>
  <span class="label">YouTube</span>
  <span class="handle">@lbenicio</span>
</a>

<a class="social-link" href="https://reddit.com/user/lbenicio" target="_blank" rel="noopener noreferrer">
  <svg viewBox="0 0 24 24" fill="currentColor"><path d="M12 0A12 12 0 0 0 0 12a12 12 0 0 0 12 12 12 12 0 0 0 12-12A12 12 0 0 0 12 0zm5.438 15.067a1.46 1.46 0 0 1-2.068 2.058c-1.26-.858-2.909-1.058-4.37-1.058-1.462 0-3.112.2-4.372 1.058a1.46 1.46 0 1 1-2.062-2.058c1.934-1.304 3.687-1.34 5.434-1.387v-.003l-.002-.006.993-4.672a.308.308 0 0 1 .364-.24l3.432.728a.933.933 0 1 1 .174.884l-3.04-.645-.895 4.23C14.971 13.724 16.777 13.76 18.723 15.06l-.002.003c.06.02-.855-4.03-.855-4.03z"/></svg>
  <span class="label">Reddit</span>
  <span class="handle">u/lbenicio</span>
</a>

<a class="social-link" href="https://buymeacoffee.com/lbenicio" target="_blank" rel="noopener noreferrer">
  <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 8h1a4 4 0 0 1 0 8h-1"/><path d="M2 8h16v9a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V8z"/><line x1="6" y1="1" x2="6" y2="4"/><line x1="10" y1="1" x2="10" y2="4"/><line x1="14" y1="1" x2="14" y2="4"/></svg>
  <span class="label">Buy Me a Coffee</span>
  <span class="handle">lbenicio</span>
</a>

</div>
