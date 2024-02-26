## Steps to reproduce the bug

Make sure you have the NCS toolchain v2.5.0 in your environment, e.g. by sourcing the generated environment script.

Clone this repository and initialize a workspace in its top directory:
```bash
git clone https://github.com/Irockasingranite/securefault-minimal-example
cd securefault-minimal-example
west init -l app
west update
```

Build and flash the application:
```bash
west build app -b nrf9160dk_nrf9160_ns -t flash
```
