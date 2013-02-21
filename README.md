## PinPost 
Pinpost is a Habari plugin that will retrive Pinboard bookmarks with a user defined tag and either create a new draft post, or append the bookmarks to an existing draft, using either HTML ordered or unordered lists, Markdown, or no formatting. It will assign a user defined tag to the draft post. Publishing is left up to the user.

###Usage
Activate the plugin at /admin/plugins. Visit your profile at /admin/user. Fill in your Pinboard username and password, the tag you would like to retrieve from Pinboard, the tag you would like to assign the new posts, a default title and how you would like to markup the bookmarks.

### Pinboard API Client in PHP
Pinpost relies on the [Pinboard API Client in PHP](https://github.com/kijin/pinboard-api) which is included with the plugin. 

###License
Pinpost is licensed under the [Apache Software License 2.0](http://www.apache.org/licenses/LICENSE-2.0.html). The Pinboard API Client in PHP is licensed under the [MIT License](http://opensource.org/licenses/MIT)
