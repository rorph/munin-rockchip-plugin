# Install

```
cp rockchip_ /usr/share/munin/plugins/
chmod +x /usr/share/munin/plugins/rockchip_
```

Add:

```
[rockchip_*]
user root

```

to your `/etc/munin/plugin-conf.d/munin-node`
then `/etc/init.d/munin-node restart`

You should see a rockchip graph under system group

