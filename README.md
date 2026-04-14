# Versa Manage

Standalone management portal for Versa sign-in system.

## Railway Setup

1. Deploy this as a new Railway project
2. Add one environment variable:
   - `MAIN_API_URL` = your main sign-in server URL
     e.g. `https://versa-manchester-production.up.railway.app`

That's it. The app proxies all API calls through to the main server.
