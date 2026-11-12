# Altbase Wallet 0.1.13 integration

Repository: `AltbaseWallet/module-pearl`.

PEARL integration now uses one raw-hex POST and durable pending-state reconciliation in the wallet/backend. Fee, MAX and final selection share reserved-input exclusions; pending spends are deducted immediately. The module keeps its existing transaction engine.

See the main wallet changelog for the complete release notes. Compilation and signing verification use isolated/public fixtures; release QA does not submit user transfers. Generated platform libraries and private wallet implementation files are excluded from new source uploads.
