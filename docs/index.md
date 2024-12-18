# Codex Docs (Archived)

```{note}
Codex is not longer being actively maintained by Wild Me at Conservation X Labs. Documentation is available in case of any independent usage. Please download the documentation as we will remove it by July 2025.
```

Codex is a web-based, multi-user software platform designed to help researchers collaboratively track individual animals in wildlife populations and estimate population size. Each Codex installation can be used by multiple researchers and organizations to study multiple species across diverse regions. Codex is also valuable as a catalog reconciliation tool.

## About Codex

This introduction covers the most common Codex interactions. It is intended to support Codex users and researchers collecting data in the field and to illustrate how to use Codex for data storage, curation, searching, and analysis.
Included Wildbook features:

* A browser-based user interface `(UI)`
* A high performance `PostgreSQL` database for storing multiple wildlife-related data types
* Two servers:
    * Data Management Server - Coordinates UI browser display and data storage
    * Wildbook Image Analysis `("WBIA")` \- Manages the computer vision pipeline and and artificial intelligence `(AI)` models and training tools. `WBIA` does not come pre-configured to detect and/or identify animals from a species. Pre-trained machine learning `(ML)` models for the species must be used, or new models must be created and configured using training data.
* Artificial intelligence `(AI)` tools to enhance image curation by:
    * Finding one or more animals in a photo or photos `("Detection")`
    * Individually identifying each animal detected `("Identification")`

```{toctree}
:hidden:
getting-started-with-codex/index
data/index
security/index
manage-users
general-faq
```

## How can you help?
Codex is no longer under active development and we are working to shut down all active platforms. See the other Wild Me products to contribute.
