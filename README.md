# mksnip

A shortcut used to quickly print snippets of code from a given directory to the console. The CLI also lists the available snippets and provides a description taken from the first 5 commented lines.

## Installation

```
$ git clone https://github.com/mkomod/mksnip
```

**Note** the script should be installed in a relevant path accessible to your bash profile, or the path made available within you bash session. *i.e.* by setting `$PATH`.


## Usage

```
Usage: mksnip [-t snip_dir] [-l] [snip_name]

Optional Arguments:
  -h, ? 		Show this help text
  snip_name		Name of the code snippet, if left blank
			a list of snippets is printed.
  -t snip_dir		Path to code snippets template
  -l			List snippets in template directory
```

## Example

```
$ mksnip -t ~/MSc/CodeTemplates/ eda.r
```

**Note** there is a default snip directory set in the source, the path should be changed, this is used as the default directory and speeds up getting snippets.



