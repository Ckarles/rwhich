# rwhich
> a "recursive" which to track binaries through symlinks

Have you ever wanted to know where the binary is **actually** located when using `which`?

Thanks to **rwhich**, the *which hunt* has never beeen easier.

```bash
$ rwhich python

/usr/bin/python
/usr/bin/python3
/usr/bin/python3.8
```

Designed to work on linux, freebsd and mac os. (So please tell me if it does not!)

I wrote this tool for multiple reasons, usually to track binaries handled by tools like `update-alternatives` and other distros equivalent.
