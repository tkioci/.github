# `$TIKOCI` — Mikrotik Container Projects

Various Mikrotik RouterOS projects, generally focused on `/container`.  See each repos for details.

Notable projects:
* **[tikoci/netinstall](https://github.com/tikoci/netinstall)**  runs Mikrotik's netinstall tool as a RouterOS container, and QEMU to enable it for ARM/ARM64.   This netinstall container uses UNIX `make` to download packages needed _automatically_ via provided `/container/env` on-demand.  Also available on [DockerHub](https://hub.docker.com/r/ammo74/netinstall).
* **[tikoci/restraml](https://github.com/tikoci/restraml)** is not a container, but contains API schemas for various RouterOS versions, using [CHR in GitHub Action](https://github.com/tikoci/restraml/actions/runs/9308686567/job/25624622673) to build the schemas.  Check out the [RouterOS Command `diff` Tool](https://tikoci.github.io/restraml) to see changes in commands across versions.
* **[tikoci/serial2http](https://github.com/tikoci/serial2http)** wraps RouterOS "remote" serial port as HTTP interface.

###

> [!NOTE]
># * Disclaimers
>
> **Use at your own risk.**  No guarantees or warranties. 
> **Any trademarks and/or copyrights remain the property of their respective holders**, unless specifically noted otherwise.
> Use of a term in this document should not be regarded as affecting the validity of any trademark or service mark. Naming of particular products or brands should not be seen as endorsements.
> Apple and Mac are registered trademarks of Apple Inc., registered in the U.S. and other countries and regions.
> MikroTik is a trademarks of Mikrotikls SIA.
> Python is a registered trademark of the PSF. 
> UNIX is a registered trademark of The Open Group.
> Docker and the Docker logo are trademarks or registered trademarks of Docker, Inc. in the United States and/or other countries. 
> Docker, Inc. and other parties may also have trademark rights in other terms used herein.
> **Follow any links at your own risk.**.  Various materials and code may contain links to other websites, content, or services.  Links are not investigated, monitored, or checked for accuracy, adequacy, validity, reliability, availability, or completeness by us.  
> **No liability can be accepted.**  No representation or warranty of any kind, express or implied, regarding the accuracy, adequacy, validity, reliability, availability, or completeness of any information is offered.  Use the concepts, code, examples and other content at your own risk. There may be errors and inaccuracies, that may of course be damaging to your system. Although this is highly unlikely, you should proceed with caution. The author(s) do not accept any responsibility for any damage incurred.  

