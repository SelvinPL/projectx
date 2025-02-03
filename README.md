Project shows how to make github action which will call action in [other repo](https://github.com/SelvinPL/projectx_using) every time release is made.

It sends tag to [other repo](https://github.com/SelvinPL/projectx_using) as parameter (other repo will use it to update submodule - which is this repo).

It requires requires `GH_TOKEN` secret which is PAT with Action read-write permissions to [other repo](https://github.com/SelvinPL/projectx_using).
