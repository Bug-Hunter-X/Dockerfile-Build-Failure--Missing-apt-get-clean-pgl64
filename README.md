This repository demonstrates a common error in Dockerfiles: forgetting to clean up after `apt-get install`.  The original `Dockerfile` results in a build failure due to excessive cache size. The `Dockerfile_fixed` shows the corrected version.