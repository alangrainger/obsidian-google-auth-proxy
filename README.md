# Transparent Google OAuth proxy for Obsidian

Google OAuth cannot use an `obsidian://` URL as a redirect URI, so this page exists to transparently pass a Google OAuth request back to Obsidian.

Use it in your plugin by specifying `https://alangrainger.github.io/obsidian-google-auth-proxy/?handler=<YOUR HANDLER ID>` as the Authorised URI Redirect.
