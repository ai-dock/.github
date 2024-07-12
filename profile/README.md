# AI-Dock

A collection of containerised AI tools you can run on your own computer or in the cloud.

AI-Dock is committed to making AI and ML accessible to all - Whether you have a high-end GPU or not.

All images are supplied with a `docker-compose.yaml` for easy startup locally (or where you have full control over a remote machine).

Images also support passing environment variables via `docker run` for customisation to ensure compatibility with container cloud providers such as [vast.ai](https://link.ai-dock.org/vast.ai).

Visit the repositories tab for all AI-dock [GPU cloud docker images](https://github.com/orgs/ai-dock/repositories).

## A note

These images defy the docker principle of one process per container - Processes are managed by supervisord because our target cloud environments only support running a single container.
