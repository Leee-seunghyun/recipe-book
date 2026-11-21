# Recipe Book

Save recipes from Instagram reels and YouTube shorts, sort their ingredients (Korean + German names) with AI, and shop for them from one list.

- `index.html`: the whole app
- `config.js`: your Supabase project address and public key
- `manifest.webmanifest`, `icons/`: lets people add the app to their home screen
- `supabase/setup.sql`: database tables and rules (run once in the Supabase SQL Editor)
- `supabase/functions/extract/index.ts`: AI relay; keeps the Anthropic API key on the server, 20 reads per person per day

The step-by-step setup guide is in the shared doc.
