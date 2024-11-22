# Example for building a custom workspace image for OpenShift Dev Spaces

__Note:__ This example assumes OCP version 4.15+ which enables `/dev/fuse` for podman builds.

If using on OCP < 4.15 then see: [3.12. Configuring fuse-overlayfs](https://docs.redhat.com/en/documentation/red_hat_openshift_dev_spaces/3.16/html/administration_guide/configuring-devspaces#configuring-fuse)

The Containerfile for this image is in the `custom-workspace-image` folder.
