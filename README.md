# wordcampus-2015-rest-api
Modified Twenty Fifteen theme with ACF JSON data for creating Artwork REST API

## Instructions

This theme is used to build a WordPress JSON REST API for a presentation at WordCamp US 2015, [“Decoupled Development with WordPress JSON APIs”](https://2015.us.wordcamp.org/session/decoupled-development-with-wordpress-json-apis/)

To use this theme:

* Create a WordPress installation on your local machine
* Add this theme, overwriting the default twentyfifteen
* Install [Advanced Custom Fields Pro](http://www.advancedcustomfields.com/pro/) (paid)
* Install [WP API v2](http://v2.wp-api.org)
* Install [ACF to WP-API](https://wordpress.org/plugins/acf-to-wp-api/)
* Install [Better REST API Featured Images](https://wordpress.org/plugins/better-rest-api-featured-images/)
* Sync the *Artwork* ACF Field Group to ACF
* Create a few Artwork posts
* Make sure your permalinks are working, and set to Post Name
* Go to [YOUR SERVER URL]/wp-json/wp/v2/artwork for JSON output