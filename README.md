# Otwellian Comments

This package converts unpolished, everyday comments into Laravel-style Otwellian comments.

It turns this:

```php
    // After the authentication service has been requested by the developer,
    // we set a variable in the application indicating the same. This tells us
    // that we need to set any queued cookies in the after event afterwards.
```

into this:

```php
    // Once the authentication service has actually been requested by the developer
    // we will set a variable in the application indicating such. This helps us
    // know that we need to set any queued cookies in the after event later.
```

Or it would, if this package actually worked. PRs accepted -- let's make this a reality!
