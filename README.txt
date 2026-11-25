PERSONAL AI ASSISTANT - STANDALONE TEST

1. Unzip this archive.
2. Create a private GitHub repository and upload index.html and vercel.json at the repository root.
3. In Vercel, choose Add New > Project, import the GitHub repository, set Framework Preset to Other, and deploy. No build command is required.
4. Open the deployed HTTPS URL, enter your Supabase publishable key and your Supabase Auth user's credentials, then click Sign in.
5. Click Extract tasks to invoke the existing extract-task Edge Function.

Project URL is prefilled. Never place an OpenAI key or Supabase secret/service-role key in the website.

If login or extraction fails, inspect the browser developer tools Network tab and the Supabase Auth/Edge Function logs. Ensure the Edge Function allows CORS preflight and the origin of your Vercel site, and that JWT verification settings match your function's own authentication logic. This starter is for testing, not a production-hardened app. Work-account integrations and WhatsApp are not included.

IMPORTANT: Revoke the OpenAI API key previously shared in chat, and replace it only in Supabase Edge Function secrets.
