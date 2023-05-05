
1. Lockfile is up-to-date, resolution step is skipped
 ERROR  Cannot install with "frozen-lockfile" because pnpm-lock.yaml is not up-to-date with packages/plugin-webpack-babel/package.json

Run pnpm install and commit the modified pnpm-lock.yaml. Then it should pass.

https://github.com/pnpm/pnpm/issues/2807


