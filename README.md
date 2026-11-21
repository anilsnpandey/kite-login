# kite-login

A one-page helper for a personal Kite Connect app. After the daily Zerodha Kite login, Kite sends the browser to this page with a one-time code. The page opens a Telegram bot, and the bot finishes the login on the owner's server.

- Nothing is stored here and there are no secrets. The code is useless without the app's secret key, which exists only on that server.
- The page removes the code from the browser history.
