@"
# 🎃 Pumpkin.fun Auto Staking Bot

A Telegram bot for automated staking on the Pumpkin.fun platform.

## Features

- 🤖 Automated staking and unstaking
- 📊 Real-time PnL tracking
- 💰 Multi-token support
- ⚡ Auto-optimization for best yields
- 🔒 Secure wallet management

## Project Structure

\`\`\`
├── src/
│   ├── bot/           # Telegram bot commands and handlers
│   │   ├── commands.py
│   │   └── handlers.py
│   ├── config/        # Configuration files
│   │   └── .env
│   ├── staking/       # Staking logic
│   │   ├── stake.py
│   │   └── unstake.py
│   ├── utils/         # Utilities and helpers
│   │   ├── mock_data.py
│   │   └── state.py
│   └── wallet/        # Wallet management
│       └── wallet.py
└── main.py           # Entry point
\`\`\`

## Documentation

For detailed documentation, see the sections in the sidebar.

## License

MIT License - see LICENSE file for details
"@ | Set-Content -Path "README.md"

# Commit and push the changes
git add README.md
git commit -m "Fix README formatting"
git push