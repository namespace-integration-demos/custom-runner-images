# Namespace Custom Runner Images
Example of using Namespace Custom Runner Images to speed up GitHub Actions

## Use Custom Runner Images

1. Go to your [Namespace Runner Profile dashboard](https://cloud.namespace.so/workspace/ghrunners);
2. Click on _New Profile_;
3. Confiugure your Runner Profile with the desired instance shape and architecture;
4. Click on _Base Image_;
5. Type any Ubuntu packages you need (e.g. `postgresql-client`);
6. Finalize the creation by clicking on _Create Profile_;
7. Use the new runner label in your workflow.

For more details see our [docs](https://namespace.so/docs/features/faster-github-actions#preview-custom-runner-image).
