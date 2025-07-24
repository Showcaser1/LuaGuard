# LuaGuard
LuaGuard
A free, client-side Lua script protection tool with whitelisting and obfuscation, inspired by LuaArmor.
Setup

Install Node.js: Get it from nodejs.org for Tailwind CSS setup.
Clone the Repo:git clone <your-repo-url>
cd luaguard


Install Tailwind CSS:npm install -D tailwindcss
npx tailwindcss init


Build CSS:npx tailwindcss -i ./src/input.css -o ./css/output.css


Serve the Site:
Use a static file server (e.g., VS Code Live Server, or npx serve).
Open index.html in your browser to test.



Features

Whitelist System: Enter a key (mock keys: demo-key-123, test-key-456) to unlock the obfuscation tool.
Script Obfuscation: Paste your Lua script and get a scrambled version.
Anti-Inspect: Dev tools (F12, right-click) are blocked to prevent tampering.
Free: No fees, just join our Discord for a key.

Security

No Server Code: Everything runs client-side, so no sensitive tokens or keys are needed.
GitHub: Safe for public repos since there’s no sensitive data. Use .gitignore to exclude node_modules and output.css.
Script Safety: Scripts are processed client-side and never stored or exposed. The anti-inspect feature blocks dev tools to prevent snooping.
Production: For a real whitelist system, add a server with Discord integration (not included here). Host on a static hosting service like Netlify or Vercel.

Notes

The whitelist and obfuscation are client-side for simplicity. For production, use a server to validate keys securely.
Replace the Discord link in index.html with your actual server link.

