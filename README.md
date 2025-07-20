# Summary
This is a simple repo that runs a grafana/promethus stack for monitoring internet stability. 

<img width="1533" height="850" alt="image" src="https://github.com/user-attachments/assets/c938822a-eaaf-4f88-b986-4101c2240037" />

<img width="1533" height="850" alt="image" src="https://github.com/user-attachments/assets/0510c3de-26cb-4f33-8f70-dadbe97b2df1" />


# How to Run
## Start the docker stack
```docker compose up```
## Access the dashbaord using the following URL
[http://localhost:3000/d/-fs18ztMz/speedtest-exporter-dashboard?orgId=1&from=now-24h&to=now&timezone=browser&var-instance=speedtest:9798&var-job=speedtest&refresh=5m](http://localhost:3000/d/-fs18ztMz/speedtest-exporter-dashboard?orgId=1&from=now-24h&to=now&timezone=browser&var-instance=speedtest:9798&var-job=speedtest&refresh=5m)

[http://localhost:3000/d/xtkCtBkiz/prometheus-blackbox-exporter?var-interval=10s&orgId=1&from=now-1h&to=now&timezone=browser&var-target=$__all&refresh=10s](http://localhost:3000/d/xtkCtBkiz/prometheus-blackbox-exporter?var-interval=10s&orgId=1&from=now-1h&to=now&timezone=browser&var-target=$__all&refresh=10s)
