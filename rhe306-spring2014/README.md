# Course Website


## Updating site

In the repository root:

    cd site
    jekyll build
    rm -rf ../../halperta.github.com/rhe309k-fall2014
    cp -rf _site ../../halperta.github.com/rhe309k-fall2014


## Development

Start the server:

    jekyll --server
    jekyll --server --auto  # recompiles html files after changes

Browse to:

    http://0.0.0.0:4000






