# microTVM Template Collection

This repository is a wrapper around several microTVM project templates. Each template is included as a Git submodule.

## Templates

| Template                       | Notes                         |
| ------------------------------ | ----------------------------- |
| `microtvm-cfu-template`        | Targeting [CDU Playground](https://cfu-playground.readthedocs.io/en/latest/) Renode, Verilator & FPGA Targets |
| `microtvm-espidf-template`     | Targeting [ESP-IDF](https://github.com/espressif/esp-idf) Targets (ESP32-C3,...) |
| `microtvm-etiss-perf-template` | Targeting [ETISS Perf Sim](https://github.com/tum-ei-eda/PerformanceSimulation_workspace)                              |
| `microtvm-etiss-template`      | Targeting [ETISS](https://github.com/tum-ei-eda/etiss)                              |
| `microtvm-gvsoc-template`      | Targeting [gvsoc](https://github.com/gvsoc/gvsoc) ⚠ Deprecated |
| `microtvm-ovpsim-template`     | Targeting [OVPSim](https://github.com/openhwgroup/riscv-ovpsim-corev) ⚠ Deprecated |
| `microtvm-spike-template`      | Targeting [Spike/`riscv-isa-sim`](https://github.com/riscv-software-src/riscv-isa-sim) with [Proxy Kernel](https://github.com/riscv-software-src/riscv-pk)* |
| `microtvm-vicuna-template`     | Targeting [Vicuna](https://github.com/vproc/vicuna) and [Vicuna2](https://github.com/vproc/vicuna2_core) vector processor |

*) Newer versions of proxy kernel might need UART/Semihosting patch.

## Cloning

Clone the repository together with all submodules:

```bash
git clone --recurse-submodules <repository-url>
```

For an existing clone, initialize and fetch the submodules with:

```bash
git submodule update --init --recursive
```

## Updating Submodules

To update all submodules to their configured remote revisions:

```bash
git submodule update --remote --recursive
```

Review and commit any resulting submodule changes in this wrapper repository.

## License

See [LICENSE](LICENSE) for licensing information.
