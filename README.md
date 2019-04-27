# Pig: Code Quality Resources

## Overview

Some code quality resources that we share and include via npm. It includes:

* [lint configurations](#lint)


## <a name="link">Lint</a>

You will find a few different configurations for linting. It is broadly broken up into `client` and `server`. Within that there are two different types of configurations one of which is normal the other which we call `relaxed`. This is meant for interactive editing. I find full on linting very distracting and this guy allows some frequently broken rules (while editing) to slide:

* [client](./client.eslintrc.json)
* [client-relaxed](./client.eslintrc.relaxed.json)
* [server](./server.eslintrc.json)
* [server-relaxed](./server.eslintrc.relaxed.json)
