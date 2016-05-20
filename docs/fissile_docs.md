## fissile docs

Has subcommands to create documentation for fissile.

### Synopsis


Has subcommands to create documentation for fissile.

### Options inherited from parent commands

```
  -c, --cache-dir string         Local BOSH cache directory. (default "/Users/vladi/.bosh/cache")
      --config string            config file (default is $HOME/.fissile.yaml)
  -f, --configgin string         Path to the tarball containing configgin.
  -d, --dark-opinions string     Path to a BOSH deployment manifest file that contains properties that should not have opinionated defaults.
  -l, --light-opinions string    Path to a BOSH deployment manifest file that contains properties to be used as defaults.
  -r, --release string           Path to dev BOSH release(s).
  -n, --release-name string      Name of a dev BOSH release; if empty, default configured dev release name will be used
  -v, --release-version string   Version of a dev BOSH release; if empty, the latest dev release will be used
  -p, --repository string        Repository name prefix used to create image names. (default "fissile")
  -m, --role-manifest string     Path to a yaml file that details which jobs are used for each role.
  -w, --work-dir string          Path to the location of the work directory. (default "/var/fissile")
  -W, --workers int              Number of workers to use. (default 2)
```

### SEE ALSO
* [fissile](fissile.md)	 - The BOSH disintegrator
* [fissile docs autocomplete](fissile_docs_autocomplete.md)	 - Generates a bash auto-complete script.
* [fissile docs man](fissile_docs_man.md)	 - Generates man pages for fissile.
* [fissile docs markdown](fissile_docs_markdown.md)	 - Generates markdown documentation for fissile.

###### Auto generated by spf13/cobra on 20-May-2016