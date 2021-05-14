# Env.exitcode

Interaction with the outside world in Pony occurs through the [`Env`](https://stdlib.ponylang.io/builtin-Env/#env) passed to `Main` on initialization. The result of this is that we must use `Env` to set our exitcode -- the method for this is `Env.exitcode` and its default value is `0` to indicate success. Any non-zero value indicates some form of failure during execution.
