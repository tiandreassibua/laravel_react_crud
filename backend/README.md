## Config
Buat migration products
isinya seperti ini :
```php
  Schema::create('products', function (Blueprint $table) {
    $table->bigIncrements('id');
    $table->string('title');
    $table->text('description');
    $table->text('image');
    $table->timestamps();
  });
```

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
