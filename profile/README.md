# About 🗂️📦

> *In a hurry? To explore the current collection of R packages in this repository, check out [collection.](https://pinasr.r-universe.dev/packages) You may also click the blue badges below for the direct link to your needs. (for finding tutorials, click articles; to check available packages, click packages)*

[![registry status badge](https://pinasr.r-universe.dev/badges/:registry)](https://pinasr.r-universe.dev/)
[![PinasR Total Packages](https://pinasr.r-universe.dev/badges/:total)](https://pinasr.r-universe.dev)
[![articles status badge](https://pinasr.r-universe.dev/badges/:articles)](https://pinasr.r-universe.dev/articles)

In the Philippines, a lot of excellent research and data code gets stranded inside academic PDFs, inactive GitHub repositories, and local hard drives, preventing other researchers from building on top of it. PinasR aims to cultivate a community culture of extending this code beyond personal computers, packaging it properly, and keeping it alive for the Filipino community.

While we are currently focused on consolidating existing Filipino packages on the Comprehensive R Archive Network (CRAN), our larger mission is to expand this infrastructure. As long as a piece of local research code is formatted as a [functional R package](https://r-pkgs.org/) on GitHub, PinasR can host and distribute it via the R-Universe infrastructure by the rOpenSci team — giving personal codes a permanent home as a means of service to the nation.

## Single-Line Installation 👨🏻‍💻
While using the R programming language for your analysis, package development, etc., you can seamlessly install all existing packages here to your own device:

```
# Enable the PinasR repository globally for your active session.
NOTE: We currently only host CRAN packages to ensure the quality of tools being loaded.

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

## FAQs ❓
* Does PinasR have communication channels (i.e., Discord) for socializing?

No. PinasR is an infrastructure meant for centralizing and distributing R packages. We believe the Filipino tech community already has existing communities that actively promotes this aspect, such as the [R Users Group - Philippines](https://www.facebook.com/rugph/) for R and [Data Science Philippines](https://www.meetup.com/data-science-philippines/) for meet-ups across programming languages. For communication, users can use existing channels within Github such as submitting an issue or creating a Pull Request.

* What makes PinasR different from other tech communities?

Unlike traditional social-first tech groups, PinasR is a code-first infrastructure project that bypasses seminars and meetups to focus entirely on centralizing existing software. It acts like a curated app store for Philippine-made R packages, allowing users to easily pick tools useful for their projects or load the entire ecosystem into their R console simultaneously. Rather than trying to add another social layer to the already vibrant local tech community, PinasR simply provides the underlying plumbing to house and distribute their code.

* How can I ensure the tools in PinasR yield accurate results for my own research?

To assure the tools yield accurate results for your research, they rely on direct methodological transparency, empirical verification, and open-source peer review. Because the entire codebase is fully public and hosted on GitHub, researchers can directly audit the raw R scripts to ensure the underlying algorithms and spatial weight formulas align precisely with established theories. When automated test suites are absent, researchers can validate accuracy by running the tools against small, manually calculated subsets of their data to verify that the mathematical logic holds true before scaling up to full-sized datasets. 

If an anomaly or calculation bias is suspected, it can be systematically isolated using a reproducible example (reprex) and cross-verified against alternative baseline packages or visual mapping plots. Furthermore, immutable version control archives every software iteration, allowing external reviewers to mirror your exact computational environment and replicate your findings. This continuous public transparency invites data engineers and statisticians to actively debate, track, and patch edge cases via the repository’s issue-tracking infrastructure, constantly sharpening the tool's reliability through collective use.

