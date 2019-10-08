# netmon
Network Monitor with Golang


## Installations
```bash
go get github.com/prometheus/client_golang/prometheus
go get github.com/prometheus/client_golang/prometheus/promauto
go get github.com/prometheus/client_golang/prometheus/promhttp

```


## Run
```bash
go run main.go

curl http://localhost:2112/metrics
```


## References
[Prometheus Example Code](https://prometheus.io/docs/guides/go-application/)
