
# rglob_files

**List all files in a directory, recursively.** [View source](https://github.com/Eiskis/Baseline-PHP/blob/master/source/glob/rglob_files.php)

	function rglob_files ($path = '', $filetypes = array() [, $secondFiletype ...])

...

**Note!** Unlike for the native `glob()`, `glob_files()` only wants the path of a directory and **not** a glob-style pattern.



## Examples

### Basics

Assume this sample directory structure for the following examples.

	documentation/about.md

	documentation/arrays/array_flatten.md
	documentation/arrays/array_traverse.md
	documentation/arrays/limplode.txt
	documentation/arrays/to_array.html

...
