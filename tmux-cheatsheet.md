# Tmux Cheatsheet

## Key Commands

Start a session

```
tmux new -s NewSession
```

Exit session

```
tmux detach
```

List sessions

```
tmux ls
```

Go back into session

```
tmux attach -t NewSession
```

## Shortcuts

- Prefix: `CTRL + t`
- Create new tmux window: `Prefix + c`
- Navigate to window: `Prefix + number`
- Cycle through window: `Prefix + n/p`
- See all windows: `Prefix + w`
- Rename window: `Prefix + ,`
- Rename session: `Prefix + $`
- Explore sessions: `Prefix + s`
- Save sessions: `Prefix + CTRL + s`
- Detach: `Prefix + d`
- Restore session: `Prefix + CTRL + r`
- Install plugins: `Prefix + I`
