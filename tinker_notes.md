# Tinker

Tinker is a CRUD like interface for ineracting with a database within a laravel project
## basics

opening Tinker
```
php artisan tinker
```

basic example
creating a post record that is composed of a title and content columns

```php
$post = table\post::create(['title'=>'post from tinker'], 'content'=>'php content from tinker'])
```

properties can be accessed like this
```php
$post->title = "new title"
```

Getting the first element of a query, or just one element where the id is 6
```
$post = App\Post::whereId(6)->first();
```

Tinker operates on eloquent and follows it's syntax

## Updating and deleting 






