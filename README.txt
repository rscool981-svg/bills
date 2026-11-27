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

NEW IN VERSION 11
- Inventory: Purchase price list and Sales price list (filter by item, party, dates).
- Stock summary hides items with zero closing stock.
- Journal: any number of Dr and Cr ledgers (+ Ledger buttons).
- Ledger groups like Tally (Add On > Ledger groups); Report > Ledger > By group.
- Day Book: money in, money out, opening, closing and difference.
- Export: one ledger/item or all; ledger statements and stock statements.
- Staff: owner adds/removes users in Add On > User, sets access limits and each person's Gmail.
- Tap any voucher row in a report to open it. Alt+P / Alt+H print or share the last saved voucher from any screen.
- Show/Hide eye on every password box.

Version 15: report paging arrows, corrected B.S./A.D. dates (A.D. shown yyyy/mm/dd), aggregate sales/purchase with units, batch, expiry, MRP, print and share, automatic Google Drive upload (refreshes in background; needs one Google sign-in per session if Google asks), custom groups that behave like standard groups, ESC steps back in PC mode, units shown in every stock report and remembered per item.

Version 16: new stock items must be given a unit when a voucher is saved (remembered afterwards); items, ledgers and units created inside vouchers now appear in Add On for editing.

Version 17: items, ledgers and units from older vouchers are added to Add On automatically.

Version 18: Add On can edit/rename ledgers, stock items, units and groups (renames update saved bills). Fixed an error when saving a ledger with no group.

Version 19: import/export by voucher type (sales, purchase, returns, receipt, payment, journal; with or without stock), template download per type and all templates in one Excel file, select-several with bulk edit/cancel/delete for vouchers, stock, ledgers and units, Google Drive subfolders per voucher type (Sales, Purchase, Receipt, Payment ...).

Version 20: ledger Excel format (voucher row + item rows, import and export, one sheet per ledger), formatted Excel entry sheets for every voucher type, styled Excel files.

Version 21: Excel registers for all sales / purchases / returns / receipts / payments / journals (voucher row + item rows), import and export, matching entry sheets.

Version 22: cash transactions on sales/purchase/returns (automatic cash receipt/payment), tap-through drill-down from reports (item > party > voucher), no discount by default, Pcs default unit, ledger list hides zero-balance parties.

v23: All reports newest first; voucher summary before opening a voucher; type = formulas in number boxes (e.g. =12*4.5+10); Utility tab (calculator, B.S./A.D. calendar and converter, cash note counter, reminder notes, Help in English/Nepali/Hindi); Manual day book with cash reconciliation (A/C Report > Books); print/share list of shortcut keys.

v24: Go To search (button, bottom right, or Alt+/) for every tab/menu/sub-menu; Analysis tab (top/least items and parties, purchases, stock groups, monthly trend, profit, slow stock); optional stock groups + stock-by-group report; Order book (customer/supplier); user-wise reports and who-changed-what log; passwords and permissions shared between devices through the company data on Google Drive; language choice (English, Nepali, Hindi, own language file, Google Translate); detailed Help with examples in English/Nepali/Hindi.

v25: Reports now run oldest to newest (downwards); Cash tick box on sales/purchase screens toggles only when the box itself is tapped (taps on the sentence or leftover taps after choosing a party are ignored); password changes are sent to Google Drive at once.

v26: Excel import with mapping like Tally: choose the worksheet, the title row and which of your columns matches each box (own Excel format works); optional batch, expiry, MRP and packing; mapping is remembered; Help rewritten.

v27: Named import templates (save, choose, delete your own column mappings per import type; shared across the company devices).

v28: Import: tick boxes to include or skip unit, batch, expiry, MRP, packing, phone, PAN, address columns.

v29 - MEMBERS (app admin only)
Members tab shows only when you log in as the app admin (master / rscool981@gmail.com).
Add each customer (name, Gmail, phone, joining, renewal, amount). "Renew 1 year" moves the date and records the payment.
Tick "Log out this member" to stop a member at any time. After the renewal date + grace days (default 7) the app locks automatically.
Reminders: use the Gmail / WhatsApp buttons (they open a ready message; you press Send). The app cannot send by itself without a server.
IMPORTANT: after every change press "Download members.json" and upload it to GitHub next to index.html. Devices read it when online and remember it for offline.
Back up the member list from the Members tab (it is stored only on your device).

v30 - More imports (Add On > Import / Export > Import > What to import)
New separate imports: Ageing / outstanding report, Stock groups, Order book. Own named templates work for all of them.
Duplicates are blocked: same name (items, parties, groups), same voucher number, same date + party + amount, same order.

v31 - Bill-wise ageing import and receipt/payment discount
Add On > Import > What to import > "Ageing report, bill-wise" (customers or suppliers). Accepts PDF (text PDFs such as Microsoft Print to PDF), Excel (report layout or flat table Party/Bill no/Bill date/Pending) and photos (needs the photo reader).
Duplicates are skipped (same party + bill no). Slabs are editable in Reports > Ledger > Ageing (default 30,45,60). Ledger has "Ageing (bill-wise)" and "+ Receipt / payment" buttons.
Receipt and Payment vouchers: Discount box. Ledger gets money + discount; cash/bank book gets money only; P&L shows discount allowed/received.

v32 - Imported ageing bills appear as lines in the party ledger/statement (ledger of a party created or set by the import shows each bill; totals unchanged). The preview asks whether the ageing is of Dr parties (debtors) or Cr parties (creditors).

v33 - Daily day book (A/C Report > Books > Daily day book (in / out))
Money in: Cash, A/c payee cheque, QR, Due. Money out: Cash, Bank, QR. Split allocation per entry (must equal total).
Expected physical cash, counted cash and gap; automatic opening/closing balance; settlement tracking (partial/full, history) for old cheques and dues - tracking only, never changes money figures; heading, daily gap, cheque, due, pending, partial and settled reports.

v34 - The money in/out day book is now THE Manual day book (A/C Report > Books > Manual day book). It is typed by the user and does not read sales or ledger. Own headings for money in and out (remembered, modifiable, with remark), heading picker for reports. The old voucher-based manual day book screen was removed (its saved counts stay in the data file).

v35 - Manual day book entry is an Excel-like grid (Money in / Money out): Heading + Cash / A/c cheque / QR / Due (out: Cash / Bank / QR) + Remarks. Heading autocomplete matches any part of the name; rows autosave; Enter/Tab/arrow navigation; paste rows from Excel. No party needed (detailed form with party/reference is under "Detailed entry").

v36 - Day book: every edit and delete (entries, headings, settlement records, counted cash, opening balance) asks for the user's password. Every entry, edit and delete is written to a day book log (who, when, before => after) stored in the company data and synced to Google Drive. View/print it in Manual day book > Reports > "Entry, edit and delete log".

v37 - Manual day book
 * Save button: saves all grid rows and the counted cash at once.
 * Old A/c payee cheque / due: one tick marks it Settled (date = settlement date box, default today). It leaves the Pending report and shows in the Settled report. Un-ticking needs the password. Tracking only: cash, bank, income, expense and day totals never change.
 * Pending report lists only items not yet settled (Pending and Partially Settled, with status).
 * Old cheque / due entries can be edited (password). The amount cannot go below part-settlements already recorded; if the amount changes the Settled tick is reset.
 * Daily gap report totals expected, counted and gap for the selected period.
 * Heading filter: search box, Tick all shown / All money in / All money out / Clear; new "Heading-wise summary" report.
 * Cash denomination counter in the day book fills the counted cash and is saved with the day.

v38 - Drill down in day book reports
 * A/c cheque, Due, Pending, Partly settled and Settled reports now have a "Settle from this report" panel: tick Settled (full) or type amount + date and Record settlement (part). Reaching zero remaining shows Fully Settled automatically. Tracking only.
 * Tap any report line to drill down: heading/gap/log lines open that day in the day book; heading-summary lines list that heading's entries; settlement lines jump to their card.

v39 - Settle button next to Share/Print on cheque and due reports; jumps to the settle cards. Tracking only.

v40 - Settle one by one
 Books > Manual day book > "Settlement tracking". Each A/c payee cheque or due is its own card.
 1. Find the item (search by party, heading, reference or date).
 2. Press Settle. Amount received shows the full remaining; change it for a part payment. Set the date received.
 3. Press Confirm settlement. Part = Partially Settled; full = Settled and the card disappears (tick "Also show fully settled items" to see it).
 No effect on day book figures. Remove a wrong record or edit the entry with your password.

v41 - Cleaner day book screen: removed the detailed-entry block between Money out and settlement (Edit this entry still opens the form); heading rename/delete moved to a collapsed box at the bottom; plain-language labels.

v42 - Removed the headings management section from the day book screen (headings still remembered automatically).

v43 - Cash rule and date reports
 * Money at end of day = Expected cash = Yesterday's closing + Total in - A/c cheque - QR - Due - Cash paid out.
 * Money out by Bank or QR is only a record; it never changes cash or the day book.
 * New reports: "Day book by date" (entries with day total; pick one date and tick headings to filter) and "Day summary by date" (one line per day).
 * Shortcuts in the day book: arrows, Enter/Tab, Ctrl+S save, PageUp/PageDown change day, Ctrl+Up/Down switch grids.
