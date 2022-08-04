# LatencyLingo

```
wget https://github.com/AnthonyBobsin/latency-lingo-cli/releases/download/v1.1.0/latency-lingo-cli_1.1.0_Linux_x86_64.tar.gz && \
tar -xzf latency-lingo-cli_1.1.0_Linux_x86_64.tar.gz

```

```
latency-lingo-cli -h
```

```
jmeter -n -t example.jmx -l Run1.log

latency-lingo-cli publish \
--file Run1.log \
--label "Hello Pubic Lingo Report"

```

```
latency-lingo-cli publish --file Run2.log \
--label "Hello Secret Lingo Report" \
--api-key 8f5c6b36-086b-5555-b6e7-999999999999

```
