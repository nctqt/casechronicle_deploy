fix docker compose networking bug and also reclaim resources

/etc/docker/daemon.json
// add:
{
  "userland-proxy": false,
  "bridge": "none"
}
