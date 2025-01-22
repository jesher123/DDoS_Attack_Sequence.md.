```mermaid
sequenceDiagram
Attacker-->BotNet: Attacker sends bots to Server
BotNet-->WebServer: Bots Spam Webserver Crashes
Webserver-->Firewall: Firewall blocks bots
Firewall-->WebServer: Attack Dismantled
```
