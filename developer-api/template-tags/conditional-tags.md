# Conditional Template Tags

Manga+Press has a few conditional template tags that work similar to Template Tags in WordPress

## is_comic()

Returns `true` if post is a comic, otherwise returns `false`. Used to detect comic posts from regular posts.

Short example of using `is_comic()`:
```php
<?php
    if (is_comic()) {
        // do something for comic posts here
    } else {
        // ignore for all other posts
    }
?>
```


## is_comic_page()
Returns `true` if page is the Latest Comic Page, otherwise returns `false`.

Short example of using `is_comic_page()`:
```php
<?php
    if (is_comic_page()) {
        // do something for Latest Comic Page here
    } else {
        // ignore for all other posts
    }
?>
```


## is_comic_archive_page()
Returns `true` if page is the Comic Archive Page, otherwise returns `false`.

Short example of using `is_comic_archive_page()`:
```php
<?php
if (is_comic_archive_page()) {
// do something for Latest Comic Page here
} else {
// ignore for all other posts
}
?>
```
