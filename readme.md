# использование в sing-box
```json
{
  "route": {
    "rules": [
      {
        "rule_set": "finalfilter",
        "action": "route",
        "outbound": "proxy"
      }
    ],
    "rule_set": [
      {
        "type": "remote",
        "tag": "finalfilter",
        "format": "binary",
        "url": "https://raw.githubusercontent.com/lzrdblzzrd/finalfilter/main/finalfilter.srs"
      }
    ]
  }
}
```

## статистика
- **дата последнего обновления:** 24.10.2026 02:39
- **ip-адреса и подсети:** 25167
- **домены:** 79191

## источники
- https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/community.lst
- https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/community_ips.lst
- https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/discord_ips.lst
- https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/domains_all.lst
- https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/ipsum.lst
- https://raw.githubusercontent.com/1andrevich/Re-filter-lists/refs/heads/main/ooni_domains.lst
- https://community.antifilter.download/list/community.lst
- https://community.antifilter.download/list/domains.lst
