# `$TIKOCI` — Mikrotik Container Projects

Various Mikrotik RouterOS projects, generally focused on `/container`.  See each repos for details.

Notable projects:
* **[tikoci/netinstall](https://github.com/tikoci/netinstall)**  runs Mikrotik's netinstall tool as a RouterOS container, and QEMU to enable it for ARM/ARM64.   "Mikrotik netinstall use UNIX `make` to download packages needed automatically via `/container/env`.  Also available on [DockerHub](https://hub.docker.com/r/ammo74/netinstall).
* **[tikoci/restraml](https://github.com/tikoci/restraml)** is not a container, but contains API schemas for various RouterOS, using [CHR in GitHub Action](https://github.com/tikoci/restraml/actions/runs/9308686567/job/25624622673).  Check out the [RouterOS Command `diff` Tool](https://tikoci.github.io/restraml) to see changes in commands across versions.
* **[tikoci/serial2http](https://github.com/tikoci/serial2http)** wraps RouterOS "remote" serial port as HTTP interface.

###

> [!NOTE]
>
> **Use at your own risk.**  No guarantees or warranties.  See [* Disclaimers](notices.md)  

