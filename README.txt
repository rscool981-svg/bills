BILL GENERATOR - web package
1. HOSTING (free, needed for Google Drive, share-as-file and offline install)
   Upload this whole folder to Netlify Drop (app.netlify.com/drop), GitHub Pages or Cloudflare Pages.
   Open the https link in Android Chrome, then menu > Install app / Add to Home screen.
   After the first load it works offline.
2. GOOGLE DRIVE (one time)
   console.cloud.google.com > new project > enable "Google Drive API" > OAuth consent screen (External, add each company Gmail as Test user)
   > Credentials > OAuth client ID > Web application > Authorized JavaScript origins = your https site address.
   Copy the Client ID. In the app: Settings > Google Drive > paste Client ID, enter that company's Gmail, tick the box, Save, then "Sign in and sync now".
   Each company uses its own Gmail and its own folder "Bill Generator - Company".
3. MOVING OLD DATA: in the old app tap Backup now, in the new app log in and use Restore backup file.
Backup files contain password hashes - keep them private.
