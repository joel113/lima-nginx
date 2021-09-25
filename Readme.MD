# Lima Nginx Example

Running lima using nerdctl on macos: https://medium.com/nttlabs/containerd-and-lima-39e0b64d2a59.

`lima nerdctl build -t lima-nginx .`

`lima nerdctl run -d -p 127.0.0.1:8080:80 lima-nginx`

`lima nerdctl ps`

`lima nerdctl stop lima-nginx`
