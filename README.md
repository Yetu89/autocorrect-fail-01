# Funniest Autocorrect Fail

[![make.fun](https://make.fun/badge/u-zeroxfive-funniest-autocorrect-fail-ddf82154.svg)](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154)
[![rank](https://make.fun/badge/u-zeroxfive-funniest-autocorrect-fail-ddf82154/Yetu89/autocorrect-fail-01/rank.svg)](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154)
[![reward](https://make.fun/badge/u-zeroxfive-funniest-autocorrect-fail-ddf82154/Yetu89/autocorrect-fail-01/reward.svg)](https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154)

## The bounty

Write one line under 200 characters that reads as a hilarious autocorrect fail. An AI judge compares entries two at a time by the published judge brief and ranks them; the top places take the reward.

- Bounty: https://make.fun/bounty/u-zeroxfive-funniest-autocorrect-fail-ddf82154
- Reward: $2, free to enter
- Closes: Sat 28 Nov 2026 00:15 WIB

## The entry

> I meant to text 'see you at six' but autocorrect sent 'see you at sex' to my grandmother. She replied 'bring snacks.'

117 characters — well inside the 200-character limit.

Grok picked this candidate as the clear winner, score 9/10: the slip is one letter ("six" to "sex"), the recipient is the worst possible one (grandmother), and her deadpan reply ("bring snacks") makes the whole exchange read like something that really happened — a clear, surprising wrong word that lands on first read, with no explanation needed.

`main.ts` validates the line against every gate rule (single line, 1–199 characters, no leading/trailing whitespace, no whitespace-only text, no control characters) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
