# lsv(-termux)

A script to list all runit services in a Termux environment.

![screenshot](https://github.com/user-attachments/assets/615ab9cf-0a60-4639-bb1e-c96d3cce188e)

## Usage

```shell
lsv [SVDIR]
```

Run `lsv` without any arguments to list services in the default `$SVDIR` path.
Optionally you can give it a custom path to look for services. 

`lsv` lists services with their run state, enabled/disabled state and PID if it's running

## Install

Simply clone the repo to a directory in your termux home.

```sh
git clone https://github.com/ulville/lsv-termux
```

Then copy the `lsv` file into  `$PREFIX/bin/`

```sh
cp ./lsv-termux/lsv $PREFIX/bin/
```

Or create a symlink

```
ln -s $HOME/.../lsv-termux/lsv $PREFIX/bin/lsv
```
