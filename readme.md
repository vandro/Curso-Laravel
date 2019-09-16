## Mi lista de comandos usados
 1164  cd /var/www/html/
 1165  mkdir curso_laravel
 1166  cd curso_laravel/
 1167  cd ..
 1168  rm -r curso_laravel/
 1169  composer create-project --prefer-dist laravel/laravel blog "5.7.*" curso_laravel
 1170  composer create-project --prefer-dist laravel/laravel curso_laravel "5.7.*"
 1171  git remote add origin git@github.com:vandro/Curso-Laravel.git
 1172  git config --local user.email "vandro.nds@gmail.com"
 1173  git config --local user.name "Vandro Laravel"
 1174  sudo chmod -R 777 storage/
 1175  php artisan make:migration create_usuario_table
 1176  artisan make:migration create_usuario_table
 1177  php artisa make:migration create_usuario_table
 1178  php artisan make:migration create_usuario_table
 1179  artisan make:migration create_usuario_table
 1180  ls
 1181  suf chmod -R artisan 
 1182  sudo chmod -R artisan 
 1183  artisan make:migration create_usuario_table
 1184  cat /home/vandro/.config/composer/vendor/bin
 1185  ls /home/vandro/.config/composer/vendor/bin
 1186  echo 'export PATH="$PATH:$HOME/.config/composer/vendor/bin"' >> ~/.bashrc
 1187  source ~/.bashrc
 1188  echo $PATH
 1189  laravel
 1190  artisan
 1191  php artisan make:migration create_usuario_table
 1192  php -v
 1193  php -h
 1194  php -v
 1195  /usr/bin/php artisan make:migration create_usuario_table
 1196  /usr/bin/php artisan migration
 1197  /usr/bin/php artisan migrate
 1198  /usr/bin/php artisan migrate:reset
 1199  /usr/bin/php artisan migrate
 1200  /usr/bin/php artisan make:migration create_rol_table
 1201  /usr/bin/php artisan make:migration create_permiso_table
 1202  /usr/bin/php artisan make:migration create_usuario_rol_table
 1203  /usr/bin/php artisan make:migration create_permiso_rol_table
 1204  /usr/bin/php artisan make:migration create_libro_table
 1205  /usr/bin/php artisan make:migration create_libro_prestamo_table
 1206  /usr/bin/php artisan migrate
 1207  /usr/bin/php artisan migrate:refres
 1208  /usr/bin/php artisan --version
 1209  composer update
 1210  /usr/bin/php artisan --version
 1211  /usr/bin/php artisan make:seeder TablaRolSeeder
 1212  /usr/bin/php artisan migrate:refres
 1213  /usr/bin/php artisan db:seed
 1214  /usr/bin/php artisan make:seeder TablaPermisoSeeder
 1215  /usr/bin/php artisan make:factory PermisoFactory
 1216  /usr/bin/php artisan make:model Models/Permiso
 1217  /usr/bin/php artisan db:seed
 1218  /usr/bin/php artisan make:controller PermisoController
 1219  /usr/bin/php artisan make:controller PermisoController -r
 1220  /usr/bin/php artisan config:clear
 1221  /usr/bin/php artisan cache:clear
 1222  composer dump-autoload
 1223  /usr/bin/php artisan make:controller PermisoController -r
 1224  /usr/bin/php artisan make:controller PermisoController -r --force
 1225  /usr/bin/php artisan make:controller PermisoController -r --plain
 1226  /usr/bin/php artisan make:controller PermisoController -r -v
 1227  /usr/bin/php artisan make:controller PermisoController -r -vv
 1228  /usr/bin/php artisan make:controller PermisoController -r -vvv
 1229* /usr/bin/php artisan make:controller PermisoController -r -vvv 
 1230  /usr/bin/php artisan make:controller PermisoController -r -vvv
 1231  /usr/bin/php artisan make:controller PermisoController -r -v
 1232  /usr/bin/php artisan make list
 1233  /usr/bin/php artisan list
 1234  /usr/bin/php artisan -h
 1235  sudo chmod -R 777 storage

## ------------------------------
<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1100 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost you and your team's skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[British Software Development](https://www.britishsoftware.co)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- [UserInsights](https://userinsights.com)
- [Fragrantica](https://www.fragrantica.com)
- [SOFTonSOFA](https://softonsofa.com/)
- [User10](https://user10.com)
- [Soumettre.fr](https://soumettre.fr/)
- [CodeBrisk](https://codebrisk.com)
- [1Forge](https://1forge.com)
- [TECPRESSO](https://tecpresso.co.jp/)
- [Runtime Converter](http://runtimeconverter.com/)
- [WebL'Agence](https://weblagence.com/)
- [Invoice Ninja](https://www.invoiceninja.com)
- [iMi digital](https://www.imi-digital.de/)
- [Earthlink](https://www.earthlink.ro/)
- [Steadfast Collective](https://steadfastcollective.com/)
- [We Are The Robots Inc.](https://watr.mx/)
- [Understand.io](https://www.understand.io/)
- [Abdel Elrafa](https://abdelelrafa.com)

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
