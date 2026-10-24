# trivy-output-test

A probe for [git-hytta](https://github.com/cge-skript/git-hytta): it runs the standard actions
of Trivy, Grype, OSV-Scanner and Snyk on deliberately outdated Python packages, to see how
findings show up in the job log and in code scanning, and how they change from one commit to
the next.

Nothing here is meant to be used.

The packages in requirements.txt change from commit to commit; some commits change nothing but this file.
