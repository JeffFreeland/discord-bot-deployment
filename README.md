# discord-bot-deployment

## Deployment instructions
- Clone the repo with `git clone https://github.com/JeffFreeland/discord-bot-deployment.git`
- Add the bot's token with `kubectl create secret generic bot-token --from-literal=TOKEN=<token>`
- Deploy with `kubectl apply -k <overlays-directory>` where `<overlays-directory>` is the desired environment (e.g., dev, or rp4)
