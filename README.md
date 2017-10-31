A simple rot-13 encoder/decoder written in Python 3.

Use it on a file:

```sh
python /path/from/root/to/rot13/dir/rot13 my_file.txt
```

Or with a pipe:

```sh
pbpaste | python /path/from/root/to/rot13/dir/rot13
```

Install by adding

```sh
export PATH="/path/from/root/to/rot13/dir:$PATH"
```

to `~/.bash_profile` (MacOS 10.12+).  Then you can run it from anywhere without including the path or invoking python directly:

```sh
rot13 myfile.txt
```

```sh
echo "test" | rot13
```

