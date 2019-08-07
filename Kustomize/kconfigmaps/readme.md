Upon running kustomize build we can see that it will replace the image name in the deployment manifest using a deplpyment-patch.yaml.
Also this appends a config map to our deployment manifest. These are specified in kustomization.yaml
