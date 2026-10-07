# my_ai_agents — TODO

- [x] need to have a stable working branch. And want to be able to make a step back. For example use have an option in my ops agent: drop my coding to a stable commit <!-- pm-task:{"id":"020c56181a8c580aa7e30b2fb47acc26","status":"done","priority":"high"} -->
- [ ] improve all ai agents ui. <!-- pm-task:{"id":"ac94eb1e6eef5bd9950370f51f83e603","status":"open","priority":"high"} -->
- [ ] need to clarify which AI model is used for. role - planning, implementing <!-- pm-task:{"id":"42c436e75c04514591ab2d095002ee8c","status":"open","priority":"normal"} -->
- [ ] backup they system, it should be scheduled and done automaically <!-- pm-task:{"id":"1e854959629f55e4b2c6d75d258d8cc7","status":"open","priority":"normal"} -->
- [ ] dashboard: RU ISP (TSPU) freezes each TLS connection to the VPS after ~7-11 KB, so Telegram Desktop gets stuck on "Loading…". Option 1 (quick): HTTP/1.1 + Connection: close for Caddy :8443, so each request gets a fresh connection (~5.5 KB each) <!-- pm-task:{"id":"cdf08e6f0f9e5c31904b2bc98f553af9","status":"open","priority":"normal"} -->
- [ ] dashboard: RU connection freeze, option 2 (robust): put the dashboard behind a CDN (e.g. Cloudflare); needs a real domain instead of sslip.io <!-- pm-task:{"id":"d558aca0e370537bbeb1e79be3e3964e","status":"open","priority":"normal"} -->
- [ ] dashboard: RU connection freeze, option 3 (client only): run Telegram Desktop through the Amnezia VPN <!-- pm-task:{"id":"ff8e11fa82585099b085644468c7e3a9","status":"open","priority":"normal"} -->
- [ ] want to see open projects PRs <!-- pm-task:{"id":"860c0b0fabda50d2ad69156fbe9c8a91","status":"open","priority":"normal"} -->
- [ ] need to implement token consumption stats <!-- pm-task:{"id":"ab4f2b176ca05b86a97d283a282cfdd3","status":"open","priority":"normal"} -->
- [ ] my future self started ai-service, should check my todo items, inspect them and provide either a implementing plan or ask the questions to clarify the task <!-- pm-task:{"id":"6346e8005b3c4c84bbf26f47a57e66be","status":"open","priority":"normal"} -->
- [ ] Alerts that come to you: have the Ops bot proactively notify me when a service fails, disk usage crosses a threshold, or a reboot is required, instead of requiring me to open the dashboard. <!-- pm-task:{"id":"eaef487d2f2147a4ac354baf782b509c","status":"open","priority":"normal"} -->
- [ ] Backups: implement automatic nightly off-server backups of env files with tokens, agent state in /var/lib/ai-*, and the Caddy configuration. Protect against losing the single VPS. <!-- pm-task:{"id":"050567438a7b47b4a6819b08aa284c83","status":"open","priority":"normal"} -->
