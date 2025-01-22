```mermaid
sequenceDiagram
Attacker-->BotNet: Attacker sends bots to Server
BotNet-->WebServer: Bots Spam Webserver Crashes
WebServer-->Firewall: Alerts Firewall
Firewall-->>WebServer: Blocks Bots
WebServer-->Firewall: Reports Success
```
