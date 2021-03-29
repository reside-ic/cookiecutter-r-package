# cookiecutter-r-package

A template for a basic R package including:

* our usual lintr template
* github workflows for check (4 platforms), coverage and pkgdown
* docker container built on buildkite
* R and git ignore files

The resulting R package should pass `R CMD check` with no notes, warnings or errors, though you will want to update the metadata in `DESCRIPTION`.

## Instructions

To create a new project run the following (no need to clone this repo first):

```shell
pip install cookiecutter
cookiecutter gh:reside-ic/cookiecutter-r-package
```

Then move the new folder somewhere, push it to GitHub and start developing

## License

MIT © Imperial College of Science, Technology and Medicine
