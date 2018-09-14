# Commitlint - Peakfijn

A simple Node image based on Alpine Linux, preinstalled with Commitlint and Peakfijn Conventions.

## Performance tweaks

- All dependencies are installed and updated within a single `RUN` statement to avoid intermediate containers.
- `npm` cache is removed or turned off to avoid large build images.
- See [`ci-node`](https://github.com/byCedric/Docker/tree/master/images/ci-node) for all other tweaks.
