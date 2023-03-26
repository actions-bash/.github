# Bash Actions

**Bash Actions** is a collection of GitHub Actions for Bourne Again SHell (Bash).

## Getting started

Choose one of the following Bash Action templates for your Action:

| Using       | Advantage                  | Disadvantage                        | Recommend to                                   |
| ----------- | -------------------------- | ----------------------------------- | ---------------------------------------------- |
| [docker]    | Container can be used.     | Need to build the image every time. | Bash that only can be run in container.        |
| [node]      | Node.js can be used.       | Need to run Bash via Node.js.       | Just run Bash.                                 |
| [composite] | Other Actions can be used. | Need to mapped inputs via env.      | Bash needs other Actions or doesn't want node. |

**Haven't decided yet? Then just use [node]!**

[docker]:https://github.com/actions-bash/docker
[node]:https://github.com/actions-bash/node
[composite]:https://github.com/actions-bash/composite

## Thanks

The [Profile picture](https://avatars.githubusercontent.com/u/127936293) is from the [GNU Bash logo](https://github.com/odb/official-bash-logo).