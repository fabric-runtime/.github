<p align="center">
  <img src="https://raw.githubusercontent.com/fabric-runtime/pi-fabric/main/media/opencollective/fabric-runtime/particle-cover.png" alt="A quiet field of warm-white particles and cobalt points on near-black" width="100%">
</p>

# Fabric Runtime

**Execute deliberately. Find the relevant code. Review with evidence.**

We build open-source tools that make agent work easier to compose, inspect, and verify: a programmable runtime, durable process orchestration, codebase discovery, and structural review.

Use the tools separately, or bring them together in [Pi](https://github.com/earendil-works/pi-coding-agent). Clear boundaries matter: explicit execution, bounded observations, and source-backed evidence—not hidden inference or a substitute for tests.

## Four projects, one working loop

| Project | What it does | Start here |
| :--- | :--- | :--- |
| **[pi-fabric](https://github.com/fabric-runtime/pi-fabric)** | A programmable tool and agent runtime for Pi. Compose tools, MCP, agents, workflows, actors, and shared coordination through `fabric_exec`. | [Install](https://github.com/fabric-runtime/pi-fabric#install) · [Execution kernels](https://github.com/fabric-runtime/pi-fabric/blob/main/docs/kernels.md) |
| **[jev-fabric](https://github.com/fabric-runtime/jev-fabric)** | A standalone native executable for durable processes, bounded logs, and explicit typed Jev decisions. Written in Bend; no Node or Python required by the native executable. | [Install](https://github.com/fabric-runtime/jev-fabric#install-it-yourself) · [Composition](https://github.com/fabric-runtime/jev-fabric/blob/main/docs/composition.md) |
| **[pi-fovea](https://github.com/fabric-runtime/pi-fovea)** | Token-budgeted codebase maps: sketch, focus, dwell, and impact across a cross-language code graph. Available in Pi and through the standalone `fovea` CLI. | [Install](https://github.com/fabric-runtime/pi-fovea#install) · [CLI guide](https://github.com/fabric-runtime/pi-fovea/blob/main/docs/cli.md) |
| **[pi-contour](https://github.com/fabric-runtime/pi-contour)** | Evidence-first structural review: before/after measurements, source witnesses, and review questions. A Pi integration and a standalone `contour` CLI—not a correctness score. | [Install](https://github.com/fabric-runtime/pi-contour#install) · [Review a patch](https://github.com/fabric-runtime/pi-contour#review-a-patch) |

## Choose your entry point

**Working in Pi?** Install the integrations you need:

```sh
pi install npm:pi-fabric
pi install npm:pi-fovea
pi install npm:pi-contour
```

See each project's installation guide for its Node and Pi requirements. Pi Fabric requires Node.js 24+ and Pi 1.0.0+.

**Working in another agent shell or CI?** Start with [jev-fabric](https://github.com/fabric-runtime/jev-fabric#install-it-yourself), the standalone **[`@monotykamary/fovea`](https://www.npmjs.com/package/@monotykamary/fovea)** package, or **[`pi-contour`](https://www.npmjs.com/package/pi-contour)** for the `contour` command. Their executable and package names are unchanged.

Fovea brings relevant code into focus; Contour reveals how its structure changes. Contour bundles the versioned Fovea substrate, so it does not require a separate Fovea installation. Jev runs independently of Pi; Pi Fabric can use it for durable process execution. Jev model calls are explicit and require your chosen provider credentials—ordinary process orchestration does not implicitly call a model.

## Build with us

Good contributions begin with reproducible evidence. Read the project's README and local contributor instructions, open a focused issue, or propose a small pull request with the checks that cover the change.

[Pi Fabric issues](https://github.com/fabric-runtime/pi-fabric/issues) · [Jev issues](https://github.com/fabric-runtime/jev-fabric/issues) · [Fovea issues](https://github.com/fabric-runtime/pi-fovea/issues) · [Contour issues](https://github.com/fabric-runtime/pi-contour/issues)

All four projects are MIT-licensed. Fabric Runtime is an independent home for these projects, not an official Pi organization.

### Support Pi Fabric

[Pi Fabric on Open Collective](https://opencollective.com/pi-fabric) supports **Pi Fabric's** maintenance, documentation, integration testing, and reproducible evaluations. It is not an organization-wide fund for all four projects.
