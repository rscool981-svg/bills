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

NEW IN THIS VERSION
- Abort button in every voucher form and in aggregate sales: erases the unfinished entry and closes the window.
- Cancelling a voucher renumbers the later vouchers of the same kind so numbers have no gap.
- Add On > Import / Export: export stock, parties, opening balances, transactions, ledger balances as Excel, PDF, JPG or PNG; import stock, parties and transactions from Excel, CSV, a photo or a PDF.
- Aggregate sales: "Fill from a photo of the notebook". Set up the photo reader first in Add On > Import / Export > Photo reader (Claude API key, or Google Drive text reader).
- Photo button ("Fill from a photo") in every voucher form. Aggregate sales return, aggregate purchase, aggregate purchase return, aggregate receipt and aggregate payment added under their menus.

NEW (photo reader v2)
- Photo reader reads unlimited entries per photo/PDF (repairs cut-off answers, 2400px images, shows exact error from Claude).
- Add On > Import / Export > "Test photo reader" checks your key; "Entry sheets" prints ready-made sheets (PDF/JPG/PNG) for sales/purchase, receipt/payment, journal.
- Stock option "Without stock": only party, date, amount, remarks (single and aggregate; sales, purchase, returns).
- Remarks are blank by default and never auto-filled.

PC / Mobile view: tap "PC view" / "Mobile view" at the top right. PC view uses the full screen with a left menu and wide entry tables. Your choice is remembered on that device.

KEYBOARD (PC)
Enter = OK / next box (last row adds a new row), Tab = next, Up/Down = rows or pick list, Left/Right = boxes in a row, Esc = close.
Settings > Version: Auto-detect / PC / Mobile.  Settings > Shortcut Keys: on/off, change any key, reset.
Defaults: Alt+S save, Alt+P print, Alt+H share, Alt+A abort, Alt+V Voucher, Alt+R Receipt, Alt+B Sales, Alt+Q Purchase, Alt+Y Payment, Alt+J Journal, Alt+L Ledger, Alt+I Inventory, Alt+T Settings, Alt+K list.

BILL PRINT: compact fonts and rows, sharper output; about 30 to 36 items fit one A4 page.

Earlier-rate popup now also opens when the cursor reaches the Rate cell by keyboard (Tab / Enter / arrows); Up/Down + Enter picks a rate.

Company name (and address/phone/PAN) now always shown at the top of every bill, voucher, statement, report and entry sheet, using the current Settings > Company details.
