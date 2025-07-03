# Buildkite Parallel Bash Pipeline Example

[![Build status](https://badge.buildkite.com/c265ae725b3643cc3434bbaec07c434c926df2bf3a96e18414.svg?branch=main)](https://buildkite.com/buildkite/bash-parallel-example)
[![Add to Buildkite](https://img.shields.io/badge/Add%20to%20Buildkite-14CC80)](https://buildkite.com/new)

This repository is an example [Buildkite](https://buildkite.com/) pipeline for running a simple bash script in parallel across multiple agents, [script.sh](script.sh).

👉 **See this example in action:** [buildkite.com/buildkite/bash-parallel-example](https://buildkite.com/buildkite/bash-parallel-example/builds/latest)

[![Add to Buildkite](https://buildkite.com/button.svg)](https://buildkite.com/new)

<a href="https://buildkite.com/buildkite/bash-parallel-example/builds/latest?branch=main">
  <img width="1503" alt="Screenshot of Buildkite parallel Bash example pipeline" src=".buildkite/screenshot.png" />
</a>

<!-- docs:start -->
## How it works

This pipeline runs a Bash script (`script.sh`) in parallel using Buildkite’s parallelism features. Each parallel step executes independently across agents.

<!-- docs:end -->

## License

See [Licence.md](Licence.md) (MIT)
