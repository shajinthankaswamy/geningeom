# geningeom – registration steps

1. GitHub organization `geningeom` – reserves the name.
2. Repository `shajinthankaswamy/geningeom` – holds the code.
3. PyPI – published automatically by `.github/workflows/publish.yml` whenever a
   tag starting with `v` (e.g. `v0.0.1`) is pushed. Uses PyPI trusted publishing,
   so no API token is stored anywhere.

To release a new version later: change `version` in `pyproject.toml`, commit,
then push a tag `vX.Y.Z`.

Keep the PyPI email reachable, push the first real code within a few weeks,
and keep Fraunhofer IISB code and data out of this repository.
