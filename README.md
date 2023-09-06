# Setup QEMU

A GitHub action for installing [QEMU](https://www.qemu.org/). Works on Linux, Windows and macOS runners.

# Example

```yaml
      - name: Setup QEMU
        uses: davidgm94/setup-qemu@v5

      - name: Run QEMU
        run:  qemu-system-x86_64 --version
```
