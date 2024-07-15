## Centava 👋


Centava governs edge-base station-kernel interactions via a procedural API that wraps around an HTTP Server API. Centava's runtime is a futures-based asynchronous runtime where nodes in Centava's DAG topology model roughly map to asynchronous tasks that communicate via channels, all scheduled by the Deno runtime. Centava implements various modules to send authenticated requests to the Kubernetes API from deno scripts. Centava allows edge orchestration via automated configuration manifests in Kubernetes to allow intelligent edge caching, offloading, inference and training.

A Centava pipeline is defined through a YAML, TOML, or JSON configuration file. For maintainability, many Centava users use configuration and data templating languages like Jsonnet or CUE.


