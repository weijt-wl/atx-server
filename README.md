# ATX-SERVER
Manage batch of atx-agents

# Usage
```
go run main.go -addr :8000
```

# APIs
## /list 接口

```bash
$ curl http://localhost:8080/list
[
    {
        "serial": "654fdaf7d340",
        "brand": "Xiaomi",
        "model": "Redmi 4A",
        "hwaddr": "",
        "ip": "10.240.218.20"
    },
    {
        "serial": "50d374ee",
        "brand": "Xiaomi",
        "model": "MI 4S",
        "hwaddr": "64:cc:2e:7a:24:2b",
        "ip": "10.242.57.253"
    }
]
```

# LICENSE
[MIT](LICENSE)