deploy
```
Deploying cluster: https://api.devnet.solana.com
Upgrade authority: /Users/levi/.config/solana/id.json
Deploying program "tic_tac_toe"...
Program path: /Users/levi/code/web3/solana/tic-tac-toe/target/deploy/tic_tac_toe.so...
Program Id: DwAMDeCVKEbsejMvV1jfYYZj97HMK9BowVmzGwtCSycR

Signature: 3PZhkenEQxdMjoT8EpWBNegQ2QF3FGMm7xa8Jb2HCn3BxzyE4fAxvC75zEEWHEepib2CCExbiPTq7b4FDUgL2NWH

Deploy success
```

test
```
Deploying cluster: https://api.devnet.solana.com
Upgrade authority: /Users/levi/.config/solana/id.json
Deploying program "tic_tac_toe"...
Program path: /Users/levi/code/web3/solana/tic-tac-toe/target/deploy/tic_tac_toe.so...
Program Id: DwAMDeCVKEbsejMvV1jfYYZj97HMK9BowVmzGwtCSycR

Signature: 5zHUkBEz4zyiiKcDRRDWHEbVqr6v6Np5dbKxt9KUFVJXkAJhwWvyvyZx7qp1khxza2RTMRCLD76b3hv48DKKS4Hv

Deploy success

Found a 'test' script in the Anchor.toml. Running it as a test suite!

Running test suite: "/Users/levi/code/web3/solana/tic-tac-toe/Anchor.toml"

yarn run v1.22.22
$ /Users/levi/code/web3/solana/tic-tac-toe/node_modules/.bin/ts-mocha -p ./tsconfig.json -t 1000000 'tests/**/*.ts'
(node:31568) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
(Use `node --trace-deprecation ...` to show where the warning was created)


  tic-tac-toe
    ✔ setup game! (6225ms)


  1 passing (6s)

✨  Done in 7.83s.
```