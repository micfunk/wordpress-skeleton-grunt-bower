# WordPress Skeleton

This is a skeleton repo for a WordPress site, originally forked from [WordpressSkeleton](https://github.com/markjaquith/WordPress-Skeleton). Here I've added some front end build tools (Grunt and Bower), along with some preloaded regularly used packages. Also some common and regularly used plugins for quicker startup.

## Assumptions

* WordPress as a Git submodule in `/wp/`
* Custom content directory in `/content/` (cleaner, and also because it can't be in `/wp/`)
* `wp-config.php` in the root (because it can't be in `/wp/`)
* All writable directories are symlinked to similarly named locations under `/shared/`.

