# Conan Config

Modified from general Conan configuration for any Bincrafter project.
Adjust remotes and profiles for traact project.
All profile values should be set except build_type

### Introduction

[Conan config](https://docs.conan.io/en/latest/reference/commands/consumer/config.html) was
released on Conan 0.27.0 providing the option to distribute and share remotes, profiles, settings.

[[Webinar] Developing C/C++ packages with Conan: new features](https://youtu.be/Aey_O86mSfg)

This project is a default template for remotes and profiles.  
Anyone is able to use and contribute.

### install

To apply this template in your current environment:

    $ conan config install https://github.com/traact/bincrafters-config.git

### Local customization

E.g If you want to set libcxx on profile linux-gcc54-amd64:

    $ conan config set compiler.libcxx=libstdc++11 linux-gcc54-amd64

## Contributing

If you want to contribute, please, create a fork or branch and submit a new PR.

## LICENSE
[MIT](LICENSE.txt)
