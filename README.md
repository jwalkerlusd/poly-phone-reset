# poly-phone-reset
poly-phone-reset is a Web App built on Lowdefy for resetting one or many Poly brand phones using the phone's built-in Web UI. It attempts with Basic, Cookie, and CSRF Auth then reports which method worked. Results are exportable to CSV.

# .env
POLY_UI_PASSWORD: LOWDEFY_SECRET_POLY_UI_PASSWORD=\<password here\>

# Use
```
git clone https://github.com/jwalkerlusd/poly-phone-reset.git

npx lowdefy@latest init && npx lowdefy@latest dev
```
Lowdefy will host at http://localhost:3000

See "dev" in the Lowdefy Docs: https://docs.lowdefy.com/cli