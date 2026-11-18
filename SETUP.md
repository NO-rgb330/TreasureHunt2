


## Forms Builder (admin)

1. Paste the updated `backend/Code.gs` into Apps Script, save, then **Deploy → Manage deployments → Edit → New version → Deploy** (the URL does not change).
2. Sign in as an admin and open **Forms Builder** in the sidebar. The `Forms` and `FormResponses` sheets are created automatically.
3. Build a form, **Save**, then use **QR & link** to copy the link, download the QR as PNG, or print a poster.
4. People who scan the QR open `<your site>/?form=<token>`. No login is needed unless you tick *Require sign-in*.
5. **Responses** shows a summary and table, and exports CSV. **Replace link** invalidates old QR codes.
