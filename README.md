# Arch Linux User Repository package for [Etcd](https://github.com/coreos/etcd)

This is **a clone** of the
[AUR Etcd package](https://aur.archlinux.org/packages/etcd/)
augmented with several patch. Commits should be self-explanatory.


## TODO

- [ ] data dir is created at install time, it thus does not belong to the
      package
- [ ] user `etcd` could be created by systemd
- [ ] file `10-EnvironmentFile` should belong to
      `/usr/lib/systemd/system/etcd.service.d`
