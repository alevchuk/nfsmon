<h2>nfsmond</h2>
```
<prob-directory>  is where you want the daemon time ls and log

The daemon has collision detection so it is safe to CRON them.
```

<h2>nfsmon</h2>
```
Usage: nfsmon <probe-log-file> [<jump-to-time>]

  <probe-log-file>  Log file where pstmd is probing
  [<jump-to-date>]  Date in YYYY-MM-DD format (Optional)

You can also put the probe filename into ~/.nfsmon then argument
<probe-log-file> becomes optional. To configure multiple probe
locations create symlinks to nfsmon executable. For example:
`ln -s nfsmon nfsmon-b` and put config into ~/.nfsmon-b
```


<h2>Screenshot</h2>
<div><img alt="" src="https://github.com/alevchuk/pstm/raw/master/ls-pings.jpg" /></div>
