# docker-fabric

My take on Fabric (the Python deploy tool) in a Docker image.

Use like the `fab` command line tool, while mapping your project directory into `/work`. If you want to use your local SSH config or keys, also volume map `$HOME/.ssh` into `/root/.ssh`.
