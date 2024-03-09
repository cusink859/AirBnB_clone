Simple file:

```sh
./w3c_validator.py index.html
```

Multiple files:

```sh
./w3c_validator.py index.html header.html styles/common.css
```

All errors are printed in `STDERR`; Exit status = # of errors (0 on success)
