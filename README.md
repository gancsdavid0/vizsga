# vizsga
--------PHP--------
laravel new example-app // létrehozza a laravel projektet

php artisan serve //elindítja a webszervert

php artisan route:list  //Ki tudod listázni a route-okat

php artisan make:component {{név}}
php artisan make:controller {{név}}        //controller létehozása
php artisan make:controller {{név}} --api  //controller létrehozása alap metódusokkal
php artisan make:model {{név}} -mfc --api  //model / factory / controller létrehozása
php artisan make:request                   // adatok validálása
php artisan make:resource                  //visszaadott JSON formázása

php artisan migrate                //Létre hozza a migrációkat
php artisan migrate --seed         //létrehozza a migrációkat és lefuttatja a seedereket is
php artisan migrate:fresh --seed   //lefrissít mindent az új változatra


--------VUE---------
npm init vue@latest    //létrehozás

npm install            //node module letöltése

npm run dev 	       //Indítás developer módban


------ANGULAR-------
ng new projektNév    				      // létrehozás
ng new carDealer --skip-tests --standalone-false      //létrehozás tesztek kihagyásával

ng serve    	     				      // Elindítás

ng generate component -fájlnév- (ng g c -fájlnév-)    //component generálásan


-----WPF---------
Add-Migration Init
Update-Database

--------Node-------
npm init
npm i express 
npm i nodemon --save-dev / -D
npm i dotenv
npm i mongoose


