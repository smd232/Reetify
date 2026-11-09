# Sukoon

Static web app: no build step, no dependencies.

## Deploy on Vercel
1. Put this folder in a GitHub repo (index.html + vercel.json at the root).
2. vercel.com > Add New > Project > import the repo. Framework preset: **Other**. Leave build/output settings empty. Deploy.
   (Or from this folder: `npx vercel --prod`.)

## Notes
- Accounts and data are stored in the browser (localStorage), per device. For real cross-device accounts, connect a backend such as Supabase or Firebase.
- Screen time, counselor chat, calls and Classroom sync are demo features (browsers cannot read device usage).
