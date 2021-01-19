## Laravel8

Berisi tentang aplikasi dengan menggunakan laravel8. File ini dibuat buat kalian yang pengen belajar laravel tapi tidak mau ribet dengan urusan instalasi di awal project.

-   sudah terinstall AdminLTE
-   sudah terinstall laravel Jetstream
-   sudah terinstall livewire (sudah otomatis ketika menginstall jetstream sih)

# installasi database

Hal yang pertama kali dilakukan setelah menginstall adalah membuat database yang baru

1. di mysql buat database baru dengan nama laravel8

# instalasi laravel Jetstream

Jika laravel tidak berjalan dengan semestinya, harap install seperti ini :

1. composer require laravel/jetstream
2. php artisan jetstream:install livewire --teams
3. npm install (pastikan sudah menginstall npm)
4. npm run dev
5. php artisan migrate
6. php artisan vendor:publish --tag=jetstream-views

# installasi AdminLTE

Jika tidak berjalan semestinya, harap install seperti ini :

1. composer require jeroennoten/laravel-adminlte
2. php artisan adminlte:install --interactive
3. pilih yes semua
4. artisan adminlte:plugins install
5. php artisan adminlte:install --only=main_views

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
