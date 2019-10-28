# ecorrect(.py) v1.0

If you've added 'eccorect' to your PATH-Variable (on linux) u can use it like this:

```sh
ecorrect <someFile>.zip
```

or:

```sh
ecorrect <someFile>.yml
```

An example `.yml` file is supplied. Change the Name and put it into your working dir. `ecorrect` will load it automatically.

If you pass the `.yml`-File to the script, you need to supply a valid `target_zip` (the example.yml should explain all possible settings). After unpacking the .zip-File it will iterate over all uploads.

The script was written for Python 3.5 and above. The Defaults have been set to work for University Ulm.

*Please Note: This script was written in ~2-3 hours. Please be kind when analyzing the code. Feel free to make any optimizations/create a pull-request.*