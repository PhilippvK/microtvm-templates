# microTVM Template Collection

This repository is a wrapper around several microTVM project templates. Each template is included as a Git submodule.

## Templates

| Template                       | Notes                         |
| ------------------------------ | ----------------------------- |
| `microtvm-cfu-template`        |                               |
| `microtvm-espidf-template`     |                               |
| `microtvm-etiss-perf-template` |                               |
| `microtvm-etiss-template`      |                               |
| `microtvm-gvsoc-template`      | ⚠ Deprecated |
| `microtvm-ovpsim-template`     | ⚠ Deprecated |
| `microtvm-spike-template`      |                               |
| `microtvm-vicuna-template`     |                               |

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
