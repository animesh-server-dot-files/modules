# Modules
These are modules for all the packages to be installed in the server

Need to add a environment variable of name `MODULE_PREFIX` which should have path in the following way `/root/home/user/installed_packages`

To download with all submodules use the following command
```
git clone --recursive git@github.com:animesh-server-dot-files/modules.git
```

To update all submodules at once use the following set of commands
```
git submodule update --init --recursive
git submodule update --recursive --remote
git pull --recurse-submodules
```

