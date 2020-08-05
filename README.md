# AntHive.IO sample bot in Go

## [Import](https://github.com/new/import) this sample bot.

## Requirements
- golang ^1.14
- Set your username in [ANTHIVE](ANTHIVE) file.
- Register your bot at https://profile.anthive.io/bots

## Debug
- git push origin master
- Register new version of your bot from latest commits
- Start new game at https://profile.anthive.io/new-game
- Replay game step by step:
  - View logs
  - Download step payload

## Run locally (not required)
```
go run main.go
```
It will start localhost server on port :7070 **Do not change port**
```
curl -X 'POST' -d @payload.json http://localhost:7070
```

### [Rules](https://anthive.io/rules/) and [Leaderboard](https://anthive.io/leaderboard/)
