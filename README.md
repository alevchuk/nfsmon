<h2>nfsmond</h2>
<pre>
Usage: ./nfsmond <prob-directory>

<prob-directory>  is where you want pstmd to ls and write the log
</pre>

<h2>nfsmon</h2>
<pre>
Usage: nfsmon <probe-log-file> [<jump-to-time>]

  <probe-log-file>  Log file where pstmd is probing
  [<jump-to-date>]  Date in YYYY-MM-DD format (Optional)

You can also put the probe filename into ~/.nfsmon then argument
<probe-log-file> becomes optional. To configure multiple probe
locations create symlinks to nfsmon executable. For example:
`ln -s nfsmon nfsmon-b` and put config into ~/.nfsmon-b
</pre>


<h2>Screenshot</h2>
<div><img alt="" src="https://github.com/alevchuk/pstm/raw/master/ls-pings.jpg" /></div>
