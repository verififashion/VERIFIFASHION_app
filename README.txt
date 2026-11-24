VERIFIFASHION - STARTER APP (not yet a complete business app)

Included: Google sign-in, persistent Firebase authentication, responsive dashboard, PWA manifest, offline shell.
Not included yet: Owner/partner role provisioning, party access, orders, payments, chat, workers, expenses, storage uploads, Firestore security rules, deployment.

NEXT STEPS
1. Use Firebase Hosting (or another HTTPS host) to serve the files in this folder.
2. In Firebase Authentication > Settings > Authorized domains, verify the hosting domain is authorized.
3. Test Google sign-in.
4. Implement owner/partner/party authorization and strict Firestore rules BEFORE enabling business data writes. Firestore production deny-all rules should remain in place until then.
5. Implement and test business workflows, uploads and payment validation before production use.

Firebase web config is a public project identifier, not a private admin key. Never publish service-account credentials.
Do not use this starter to store real business or customer data yet.
