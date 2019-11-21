# rm_build

Script to find and remove build scripts.

>   **Disclaimer**
>   
>   This library is free to use under the [MIT license](https://github.com/tdegeus/rm_build/blob/master/LICENSE). Any additions are very much appreciated, in terms of suggested functionality, code, documentation, testimonials, word-of-mouth advertisement, etc. Bug reports or feature requests can be filed on [GitHub](https://github.com/tdegeus/rm_build). As always, the code comes with no guarantee. None of the developers can be held responsible for possible mistakes.
>   
>   Download: [.zip file](https://github.com/tdegeus/rm_build/zipball/master) | [.tar.gz file](https://github.com/tdegeus/rm_build/tarball/master).
>   
>   (c - [MIT](https://github.com/tdegeus/rm_build/blob/master/LICENSE)) T.W.J. de Geus (Tom) | tom@geus.me | www.geus.me | [github.com/tdegeus/rm_build](https://github.com/tdegeus/rm_build)

# Contents

# Getting rm_build

## Using conda

```bash
conda install -c conda-forge rm_build
```

## From source

```bash
# Download rm_build
git checkout https://github.com/tdegeus/rm_build.git
cd rm_build

# Install
cmake .
make install
```
# Create a new release

1.  Update the version number in `rm_build`. 

2.  Upload the changes to GitHub and create a new release there (with the correct version number).

3.  Update the package at [conda-forge](https://github.com/conda-forge/rm_build-feedstock).

