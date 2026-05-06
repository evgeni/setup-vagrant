# Set up Vagrant

Sets up Vagrant with Libvirt

For Ubuntu 24.04 the [evgeni/vagrant PPA](https://launchpad.net/~evgeni/+archive/ubuntu/vagrant) is used, as Ubuntu doesn't ship Vagrant anymore.

## Example

```yaml
jobs:
  tests:
    name: "Run Vagrant-based tests"
    runs-on: ubuntu-latest
    steps:
      - uses: voxpupuli/setup-vagrant@v0
      - …
```
