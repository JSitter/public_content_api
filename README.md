# Public Content API Module
This module is a work in progress which will allow for the use of the [Backdrop CMS](https://backdropcms.org/) as a backend for a decoupled front end of your choice. It returns the requested data using in JSON for consumption by your front end.

## Planned Pages
Configuration Page: `/admin/config/administration`.

Planned options:
* `/most-active` Default returns the top 25 most active posts.
* `/most-active/?page=2` for the next most popular posts.
* `/most-active/article/` for the most active posts of a certain content type.
* `/most-active/article/?page=2` for the next most popular posts of a given content type.
* `/get/article/1` Gets Content type with given node id.

## License
MIT
