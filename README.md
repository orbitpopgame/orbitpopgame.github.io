# ORBIT POP links

Web pages for ORBIT POP (Barrio Games):

- `/duel/?c=ORBIT-...` — a duel invitation. With the game installed, Android opens ORBIT POP
  directly (App Links); otherwise this page shows the challenge, the Google Play link and the
  tester sign-up.
- `/.well-known/assetlinks.json` — proves to Android that these links belong to the app
  `com.barriogames.orbitpop`.

The source lives in the game repository (`site/`).
