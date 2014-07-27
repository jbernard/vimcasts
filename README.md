## Vimcasts

A git annex repository of Vimcast episodes.

This allows you to selectively fetch and store locally any episodes you wish to
view or use as a reference.  I find myself doing this often, especially for the
fugitive series.

## Usage

To use this repository, you must have `git` and `git-annex` installed.

To fetch a particular episode in OGV format:

    git annex get 01/show_invisibles.ogv

To fetch all episodes in m4v format:

    git annex get */*.m4v

See the [git-annex](http://git-annex.branchable.com/) documentation for further
information.
