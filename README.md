# ansible-windows-remote-desktop

## Requirements

## Role Variables

```yaml
---
# defaults file for ansible-windows-remote-desktop

windows_remote_desktop_enabled: true

windows_remote_desktop_firewall: []
  # - name: Remote Desktop
  #   action: allow
  #   description: Disabled Default Remote Desktop Rule
  #   direction: in
  #   enable: false
  #   force: true
  #   localport: 3389
  #   protocol: TCP
  #   state: present
  # - name: Remote Desktop - Any
  #   action: allow
  #   description: Allow Remote Desktop From Any
  #   direction: in
  #   enable: true
  #   force: true
  #   localport: 3389
  #   profile: any
  #   protocol: TCP
  #   remoteip: any
  #   state: present
  # - name: Remote Desktop - 192.168.250.0/24
  #   action: allow
  #   description: Allow Remote Desktop From 192.168.250.0/24
  #   direction: in
  #   enable: true
  #   force: true
  #   localip: '{{ ansible_ssh_host }}'
  #   localport: 3389
  #   profile: any
  #   protocol: TCP
  #   remoteip: 192.168.250.0/24
  #   state: present
```

## Dependencies

## Example Playbook

## License

MIT

## Author Information

Larry Smith Jr.

-   [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
-   [EverythingShouldBeVirtual](http://www.everythingshouldbevirtual.com)
-   [mrlesmithjr.com](http://mrlesmithjr.com)
-   mrlesmithjr [at] gmail.com
