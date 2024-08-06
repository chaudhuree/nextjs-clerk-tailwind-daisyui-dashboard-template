## create .env.local file at the root.
## login to the clerk dashboard. copy the key and paste it into .env.local file 
```sh
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=/*we will get it from clerk dashboard after login*/
CLERK_SECRET_KEY=/*we will get it from clerk dashboard after login*/
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
```