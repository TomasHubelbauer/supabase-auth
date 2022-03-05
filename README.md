# Supbabase Auth

This is a test repository meant for me to be able to prototype a Supabase Auth
based application.

Step by step what I've done so far:

1. Scaffold a new Next application
2. Create a new Supabase project named `supabase-auth`
  - Database password is in `secrets.txt` (Git-ignored)
  - Free tier

The end goal is to have a Next application that uses Supabase Auth to log in and
out a single user and does not allow any other users to sign up. This is meant
to be a single-user application. The application will allow managing a set of
items using Supabase CRUD APIs.

## Running

`npm run dev`
