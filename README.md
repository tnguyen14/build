## Usage

Create `hooks/post_push` file with the following content:

```sh
#!/bin/bash

curl -sL https://raw.githubusercontent.com/tnguyen14/build/master/dockerhub/hooks/post_push | bash
```
