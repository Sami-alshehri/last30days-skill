**☁️ Cloud & Identity**
- Postmodern Templates proposed enforcing default restricted Pod Security Standards in Helm charts to prevent containers from running as root <https://github.com/postmodern-templates/helm-chart-template/issues/77>
- OpenShift GitOps Lab implemented container hardening patterns including unprivileged runtimes, read-only root filesystems, and dropped capabilities <https://github.com/P-Liebler/OpenShift-GitOps-Lab/pull/1>
- OpenShift fixed a Trivy security scanning job failure caused by strict read-only root filesystem policies lacking a writable `/tmp` directory <https://github.com/openshift/release/pull/88156>
- CloudOpsBench released a benchmark evaluating foundational AI models on cloud infrastructure operations <https://cloudopsbench.ai>
Why it matters: Enforcing strict Pod Security Standards and read-only container filesystems mitigates runtime security risks, but operational configurations like temporary storage mounts are essential to prevent security scanners from breaking.
