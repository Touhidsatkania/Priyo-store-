PRIYO STORE V89 — Login + Password Recovery Fix

Fixes:
- Real Supabase session is preserved for both trusted-device login and first-device verification.
- Verification no longer opens Dashboard with a missing/invalid session.
- Forgot Password now calls Supabase /auth/v1/recover and reports success/error.
- Removed the old Admin-login instruction from the Login UI.
- Android versionCode 89 / versionName 1.0.89.
- GitHub Actions uploads one canonical artifact: PRIYO-STORE-V89-APK / PRIYO-STORE-V89.apk.
- Workflow validates source version and authentication/recovery code before building.
