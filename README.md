![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n - Secure Workflow Automation for Technical Teams

n8n is a workflow automation platform that gives technical teams the flexibility of code with the speed of no-code. With 400+ integrations, native AI capabilities, and a fair-code license, n8n lets you build powerful automations while maintaining full control over your data and deployments.

![n8n.io - Screenshot](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## Key Capabilities

- **Code When You Need It**: Write JavaScript/Python, add npm packages, or use the visual interface
- **AI-Native Platform**: Build AI agent workflows based on LangChain with your own data and models
- **Full Control**: Self-host with our fair-code license or use our [cloud offering](https://app.n8n.cloud/login)
- **Enterprise-Ready**: Advanced permissions, SSO, and air-gapped deployments
- **Active Community**: 400+ integrations and 900+ ready-to-use [templates](https://n8n.io/workflows)

## Quick Start

Try n8n instantly with [npx](https://docs.n8n.io/hosting/installation/npm/) (requires [Node.js](https://nodejs.org/en/)):

```
npx n8n
```

Or deploy with [Docker](https://docs.n8n.io/hosting/installation/docker/):

```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n docker.n8n.io/n8nio/n8n
```

Access the editor at http://localhost:5678

## Resources

- 📚 [Documentation](https://docs.n8n.io)
- 🔧 [400+ Integrations](https://n8n.io/integrations)
- 💡 [Example Workflows](https://n8n.io/workflows)
- 🤖 [AI & LangChain Guide](https://docs.n8n.io/advanced-ai/)
- 👥 [Community Forum](https://community.n8n.io)
- 📖 [Community Tutorials](https://community.n8n.io/c/tutorials/28)

## Support

Need help? Our community forum is the place to get support and connect with other users:
[community.n8n.io](https://community.n8n.io)

## License

n8n is [fair-code](https://faircode.io) distributed under the [Sustainable Use License](https://github.com/n8n-io/n8n/blob/master/LICENSE.md) and [n8n Enterprise License](https://github.com/n8n-io/n8n/blob/master/LICENSE_EE.md).

- **Source Available**: Always visible source code
- **Self-Hostable**: Deploy anywhere
- **Extensible**: Add your own nodes and functionality

[Enterprise licenses](mailto:license@n8n.io) available for additional features and support.

Additional information about the license model can be found in the [docs](https://docs.n8n.io/sustainable-use-license/).

## Contributing

Found a bug 🐛 or have a feature idea ✨? Check our [Contributing Guide](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md) for a setup guide & best practices.

## Join the Team

Want to shape the future of automation? Check out our [job posts](https://n8n.io/careers) and join our team!

## What does n8n mean?

**Short answer:** It means "nodemation" and is pronounced as n-eight-n.

**Long answer:** "I get that question quite often (more often than I expected) so I decided it is probably best to answer it here. While looking for a good name for the project with a free domain I realized very quickly that all the good ones I could think of were already taken. So, in the end, I chose nodemation. 'node-' in the sense that it uses a Node-View and that it uses Node.js and '-mation' for 'automation' which is what the project is supposed to help with. However, I did not like how long the name was and I could not imagine writing something that long every time in the CLI. That is when I then ended up on 'n8n'." - **Jan Oberhauser, Founder and CEO, n8n.io**


N8N_HOST=rigdocaisearch.nov.com
N8N_PORT=8073
N8N_PROTOCOL=http
WEBHOOK_URL=http://rigdocaisearch.nov.com:8073/
N8N_Listen_Address=0.0.0.0
N8N_SECURE_COOKIE=false
N8N_ENCRYPTION_KEY=12345678
DB_TYPE=sqlite
EXECUTIONS_DATA_PRUNE=true
EXECUTIONS_DATA_MAX_AGE=168
EXECUTIONS_DATA_PRUNE_MAX_COUNT=50000
GENERIC_TIMEZONE=America/New_York
N8N_LOG_LEVEL=info

pnpm turbo run dev --parallel --env-mode=loose --filter=!@n8n/design-system --filter=!@n8n/chat --filter=!@n8n/task-runner --filter=!n8n-playwright

set N8N_HOST=rigdocaisearch.nov.com&& set N8N_PORT=8073&& set N8N_PROTOCOL=http&& set WEBHOOK_URL=http://rigdocaisearch.nov.com:8073/&& set N8N_Listen_Address=0.0.0.0&& pnpm turbo run dev --parallel --env-mode=loose --filter=!@n8n/design-system --filter=!@n8n/chat --filter=!@n8n/task-runner --filter=!n8n-playwright


set N8N_HOST=rigdocaisearch.nov.com&& set N8N_PORT=8073&& set N8N_PROTOCOL=http&& set WEBHOOK_URL=http://rigdocaisearch.nov.com:8073/&& set N8N_Listen_Address=0.0.0.0&& node packages/cli/bin/n8n start
set N8N_HOST=rigdocaisearch.nov.com&& set N8N_PORT=8073&& set N8N_PROTOCOL=http&& set WEBHOOK_URL=http://rigdocaisearch.nov.com:8073/&& pnpm turbo run dev --parallel --env-mode=loose --filter=!@n8n/design-system --filter=!@n8n/chat --filter=!@n8n/task-runner --filter=!n8n-playwright


set N8N_HOST=rigdocaisearch.nov.com&& set N8N_PORT=8074&& set N8N_PROTOCOL=http&& set WEBHOOK_URL=http://rigdocaisearch.nov.com:8074/&& set N8N_Listen_Address=0.0.0.0&& node packages/cli/bin/n8n start




set N8N_USER_FOLDER=C:\projects\rajan8n\n8n\.n8n&& set PLAYWRIGHT_BROWSERS_PATH=C:\projects\rajan8n\n8n\.ms-playwright&& set N8N_HOST=rigdocaisearch.nov.com&& set N8N_PORT=8074&& set N8N_PROTOCOL=http&& set WEBHOOK_URL=http://rigdocaisearch.nov.com:8074/&& set N8N_LISTEN_ADDRESS=0.0.0.0&& set N8N_SECURE_COOKIE=false&& node packages/cli/bin/n8n start
