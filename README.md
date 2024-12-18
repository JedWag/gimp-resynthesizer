# GIMP 2 Resynthesizer Plugin

This project builds on [resynthesizer-scm](https://github.com/itr-tert/gimp-resynthesizer-scm), replacing the deprecated Python 2 code from the original [resynthesizer](https://github.com/bootchk/resynthesizer) with `Script-Fu`. By simplifying it's menu and removing the distracting `(scm)` suffix from items, it further enhances usability.

## Installation - Build from source

1. **Navigate to the Root Directory**: After downloading the source code, navigate to the repository's root directory.
2. **Run `autogen.sh`**: The `autogen.sh` script prepares the build environment. It runs tools like _autoreconf_ to generate necessary files such as configure.

```bash
./autogen.sh
```

3. **Compile with make**: After `autogen.sh` completes, run `make` to compile the plugin:

```bash
make
```

4. **Install the Plugin**: Use `sudo make install` to copy the compiled plugin files to the system-wide **_GIMP_** directories:

```bash
sudo make install
```

## Resources

- [Resynthesizer Wiki](https://github.com/bootchk/resynthesizer/wiki)
- [User's Guide](https://github.com/bootchk/resynthesizer/wiki/Quick-user's-guide-to-the-Resynthesizer-plugins-for-GIMP)
- [Developer's Guide](https://github.com/bootchk/resynthesizer/wiki/Developer's-guide-to-the-Resynthesizer-code-and-dependencies)
- [GIMP 3 Resynthesizer](https://github.com/bootchk/resynthesizer/wiki/Resynthesizer-and-GIMP-version-3)
