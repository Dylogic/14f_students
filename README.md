# Students CRUD API

## artisan parancsok
Új migráció létrehozása
```php artisan make:migration create_students_table```

Migrációk lefuttatása
```php artisan migrate```

Utolsó migráció visszavonása
```php artisan migrate:rollback```

Elkezdeni előröl
```php artisan migrate:fresh```

Model létrehozása
```php artisan make:model Student```
ajánlott: model Nagybetűvel kezdődik és egyesszám, hozzá a tábla kisbetűs többesszám.
ajánlott: angol

Factory létrehozása(fake adatok generálása)
```php artisan make:factory Student```

Seeder futtatása
```php artisan db:seed```

Migrációs és a seedelés egyben
```php artisan migrate --seed```
```php artisan migrate:fresh --seed```

Controller osztály létrehozása
```php artisan make:controller StudentController```

Api metódusokkal együtt
```php artisan make:controller StudentController --api```

All in One
```php artisan make:model Teacher -mfc --api```

Route útvonlalak listázása
```php artisan route:list```

## ThunderClient export
thunder-collection-14f_students.json