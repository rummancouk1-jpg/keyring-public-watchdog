# Keyring public watchdog

This public repository checks only Keyring's public, data-free health endpoint.
It has no repository secrets, no authentication token, and no access to customer
or workspace data.

Target: `https://keyring-gamma.vercel.app/api/health`

The 30-minute schedule lives here so it does not consume the private Keyring
repository's Actions allowance.
