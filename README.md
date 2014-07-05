# node-glfw3

glfw3 sourcecode and a static build target

# abstract

This module provides the source code for glfw3 and a gyp file that will build a static target

The idea here is that it is _way_ better to link statically than depend on a user having a
dependency satisfied on their system.

# install

```npm install glfw3```

# use

add this to your gyp file:

```javascript
  'bindings' : [
    'node_modules/glfw3/binding.gyp:glfw3-static'
  ]
```



