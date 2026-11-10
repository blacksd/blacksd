# Marco Bulgarini

Staff SRE at [HiveMQ](https://www.hivemq.com), based in Milan (CET). I build Kubernetes platforms with reliability as a core pillar, and I am a [CNCF Kubestronaut](https://www.credly.com/users/marco.bulgarini).

Most of my day-to-day work lives in private repositories. This is what I can show:

- **[kube-on-the-cheap](https://github.com/kube-on-the-cheap)**: my homelab, run like production on a hobby budget. Two Kubernetes clusters (Talos on-prem, OKE on the Oracle Cloud free tier) on a Tailscale tailnet, provisioned with Terragrunt and reconciled with Flux.
- **[crd-schema-extractor](https://github.com/blacksd/crd-schema-extractor)**: a Go tool that pulls CRDs from Helm charts (HTTP and OCI), release manifests and GitHub archives, and turns them into standalone JSON Schemas with provenance metadata and a CycloneDX SBOM.
- **[crd-schemas](https://github.com/blacksd/crd-schemas)**: the extractor's output, versioned per upstream release and ready for [kubeconform](https://github.com/yannh/kubeconform) to validate custom resources in CI.
- **[nix](https://github.com/blacksd/nix)**: my machines, declared in Nix.

[LinkedIn](https://www.linkedin.com/in/marcobulgarini) · [Credly](https://www.credly.com/users/marco.bulgarini)
