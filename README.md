# Cubit Library
Founder-facing company asset navigator.

## Live
https://cubitsystemsinc.netlify.app/library/

## Purpose
One-tap folder/file navigation for Head Offices assets — replace unreliable phone Drive directory hunting.

## Features (v0.1)
- Company tree (Boardroom, Finance, OS product, Games, IT, Accounting, Uploads)
- Breadcrumb navigation · Up · Root
- Open links/docs/APK release URLs
- Upload files (stored on-device in Uploads for this version)
- PWA-capable (Add to Home Screen)

## APK path
Wrap `www/` with the same WebView/Capacitor approach as Head Offices.  
Android cannot expose full device filesystem without SAF permissions; Library owns **company asset space** first (doctrine: assimilation before promising root access).

## Next assimilation
- Drive API list/upload into real folders
- Download to device Downloads via browser/APK
- IT owns extremity health for Library CI release
