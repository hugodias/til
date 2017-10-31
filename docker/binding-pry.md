# Binding.pry on docker

When coding rails we usually use binding.pry to debug the code.

On docker we need to attach to the web container to be able to do that.

In another tab or window, just run the following command:

```bash
docker attach awesome-app
```
