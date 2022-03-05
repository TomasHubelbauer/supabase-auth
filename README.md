# Supbabase Auth

This is a test repository meant for me to be able to prototype a Supabase Auth
based application.

Step by step what I've done so far:

1. Scaffold a new Next application
2. Create a new Supabase project named `supabase-auth`
  - Database password is in `secrets.txt` (Git-ignored)
  - Free tier
3. Set up a new Vercel project based on this repository
  - https://supabase-auth-sage.vercel.app
4. Link up the local repository and the Vercel project
5. Update the Vercel Supabase integration to apply to this project

I got stuck here, because the Supabase integration did not install the Supabase
environment variables to the Vercel project. I could manage them manually, but I
would like for this to work the same way it works for my other Vercel projects.

I opened a support case and tweeted out my problem, will pick up when I have a
lead on how to get this fixed.

The end goal is to have a Next application that uses Supabase Auth to log in and
out a single user and does not allow any other users to sign up. This is meant
to be a single-user application. The application will allow managing a set of
items using Supabase CRUD APIs.

## Running

`npx vercel dev`
