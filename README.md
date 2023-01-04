# build-fe

### Inputs:

| Name  | Required | Details | Default value |
| :---: | :------: | :-----: | :-----------: |
| aws-access-key | yes | | |
| aws-secret-access-key | yes | | |
| aws-region | yes | | |
| aws-s3-name | yes | | |
| aws-cloudfront-name | yes | | |
| slack-channel | yes | | |
| slack-token | yes | | |
| build-command | no | [`yarn`, `npm`] | `yarn` |
| app-envs | no | | |
| build-path | no | | `build` |
| node-version | no | | 16.x |
