# Poll Bot

Matrix bot to do polls.

Fork of the original [matrix-poll-bot](https://github.com/babolivier/matrix-poll-bot/).
Some tweaks were made. In particular, poll options are inlined 
in the original message instead being spammed with a long message 
from the bot host.


## Build

```bash
git clone https://github.com/jota191/matrix-polls.git
cd matrix-poll-bot
go build
```

## Run

```
./matrix-poll-bot --config /path/to/config.yaml
```

## Configure

See [config.sample.yaml](/config.sample.yaml).
