# Public Content API Module
This modules is a work in progress which will allow for easily returning content to a headless front end using JSON.

## Pages
Configuration Page: `/admin/config/administration`.

Planned options:
* `/most-active` Default returns the top 25 most active posts.
* `/most-active/?page=2` for the next most popular posts.
* `/most-active/article/` for the most active posts of a certain content type.
* `/most-active/article/?page=2` for the next most popular posts of a given content type.
* `/get/article/1` Gets Content type with given node id.

## License
MIT
