# About 📚☀️🌴

> *In a hurry? To explore the current collection of R packages in the repository, check out [collection.](https://pinasr.r-universe.dev/packages) You may also click the badges below for the direct link to your needs (for finding tutorials, click articles; for the packages available, click packages)*

[![registry status badge](https://pinasr.r-universe.dev/badges/:registry)](https://pinasr.r-universe.dev/)
[![PinasR Total Packages](https://pinasr.r-universe.dev/badges/:total)](https://pinasr.r-universe.dev)
[![articles status badge](https://pinasr.r-universe.dev/badges/:articles)](https://pinasr.r-universe.dev/articles)

**PinasR** is an independent, community-driven software registry dedicated to consolidating, building, and distributing R packages tailored to the unique geographic, socioeconomic, and ecological landscape of the Philippines. By fully leveraging the specialized features of the R-Universe infrastructure, this repository serves as a centralized, high-performance platform that champions the open-source movement across the archipelago.

## Single-Line Installation
While using the R programming language for your analysis, package development. etc., you can seamlessly install all existing packages here to your own device:

```
# Enable the PinasR repository globally for your active session. NOTE: We currently only host CRAN packages to ensure the quality of tools being loaded.
options(repos = c(
  pinasr = "https://r-universe.dev",
  CRAN = "https://r-project.org"
))

# Example: Install a specific package directly from the PinasR universe
# replace "palettephines" with any package name in the ecosystem
install.packages("palettephines")
```
## Key R-Universe Integration 🚀
* **Instant Session Setup:** Users can integrate the entire Philippine R ecosystem into their active R session with a single line of code, ensuring seamless loading without manual installation struggles.
  
* **Cross-Platform Compilation:** The platform handles automatic building and testing across Linux, macOS, and Windows environments, providing ready-to-use binaries for every user.
  
* **Global Discoverability: Every package is indexed with structured metadata, interactive documentation, and real-time health dashboards to maximize the visibility of Filipino-led scientific tools.**
  
* **Automated Syncing: The registry links directly to package repositories, instantly pulling updates, tracking commits, and serving the latest development builds without developer overhead.**

## Sali Na! (How to Contribute) 🔗‍💥

To contribute, you just need to update the `packages.json` file in [this](https://github.com/pinasr/pinasr.r-universe.dev) repository. Once the Pull Request is merged, the PinasR bot will automatically detect your package, build the binaries for Windows, Mac, and Linux, and feature it on our official registry. For concerns that you haven't settled despite online research, you may get in touch [here.](ninotalingting77@gmail.com).
