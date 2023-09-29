## sst-demo

This repo is deployed to AWS via SST, an infrastructure-as-code framework.

First, ensure that AWS access keys and secrets are set up.

1. Run `aws configure`

Then, to deploy locally:

1. Run `pnpm i`
2. Run `pnpm sst dev`

To deploy to production:

1. Run `pnpm sst deploy --stage prod`
