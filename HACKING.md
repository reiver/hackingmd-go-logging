# HACKING: Logging in Golang

This `HACKINGS.md` document describes how to deal with **logging** in the **Go programming-lanuage** (**golang**).

-----

## Do Not

In general, do _not_ use the Go built-in packages for **logging**.
I.e., in general, do not use the Go built-in [`"log"`](https://pkg.go.dev/log) package, do not use the Go built-in [`"log/slog"`](https://pkg.go.dev/log/slog) package, and do not use the Go built-in [`"log/syslog"`](https://pkg.go.dev/log/syslog) package.

## Do

Instead use the following package for **logging**:

* https://codeberg.org/reiver/go-log
