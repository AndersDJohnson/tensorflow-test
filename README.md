# tensorflow-test

Snowpack + TypeScript giving `default` errors? Thinking face Solved by replacing `obj.__esModule` with `obj.__esModule || obj.default` and `mod.__esModule` for `(mod.__esModule || mod.default)` for files under `node_modules/.cache/snowpack/development` & restarting `snowpack dev`.
