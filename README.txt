MEDBOOKS - web package
1. HOSTING (free; needed for Google Drive, share-as-file and offline install)
   Upload this whole folder to GitHub Pages, Netlify Drop or Cloudflare Pages.
   Open the https link in Android Chrome, then menu > Install app / Add to Home screen.
   After the first load it works offline.
   Replacing an older version: upload the files over the old ones. Existing data on the phone is kept.
2. GOOGLE DRIVE (one time)
   console.cloud.google.com > new project > enable "Google Drive API" > OAuth consent screen (External, add each company Gmail as Test user)
   > Credentials > OAuth client ID > Web application > Authorized JavaScript origins = your https site address.
   In the app: Add On > Company > Google Drive: paste Client ID, enter that company's Gmail, tick the box, Save, then "Sign in and sync now".
   Each company uses its own Gmail and its own folder "MEDBOOKS - Company".
3. MENU: Voucher entry | A/C report | Inventory | Print/Share | Modify voucher (password) | Add On (ledger, stock, units, user, company, voucher settings).
4. FISCAL YEAR: Add On > Company > Fiscal year closing. Closing locks the year; balances carry forward automatically. The owner can reopen it.
5. DELETE COMPANY: Add On > Company > Delete company (password, type the name; a backup file is downloaded first).
Backup files contain password hashes - keep them private.
