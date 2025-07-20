## Terraform Module Template Example

With OpenTofu 1.10.0, OCI Registry support is now [included](https://opentofu.org/blog/opentofu-1-10-0/). This means we can now use Github Packages as a private or public terraform module registry!

This repo is an example on how a full workflow would look like under Github Actions.

To show the full process, stuff like semantic-release is installed directly in the workflow instead of through more efficient means such as containers.
