<h2> LARAVEL TEMPLATE 5.2.0 </h2>
<p> Este proyecto en un template para crear proyectos Laravel via instalador laravel version 5.2.0 </p>
<p> Cuando clones este proyecto recuerda que debes hacer el siguiente proceso: 
<ul>
    <li> Crear carpeta vendor proyecto
        <ul> SHELL
            <ol> composer install </ol>
        </ul>    
    </li>
    <li> Clonar archivo env.example a env 
        <ul> SHELL
            <ol> cp .env.example .env </ol>
        </ul>     
    </li>
    <li> Generar clave de la nueva aplicacion
        <ul> SHELL
            <ol> php artisan key:generate </ol>
        </ul>    
    </li>
    <li> Para hacer mas flexible, he puesto SQLITE. Luego puedes usar MYSQL, MariaDB,.. Recuerda cambiar en .env DB_CONNECTION según gustos.
        <ul> SHELL
            <ol> touch database/database.sqlite </ol>
            <ol> chmod 664 database/database.sqlite </ol>
        </ul>        
    </li>
    <li> Recuerda migrar base datos 
        <ul> SHELL
            <ol> php artisan migrate </ol>
        </ul>    
    </li>
    <li> Finalmente, ya puedes usar php artisan serve. Recuerda puedes mirar logs de proceso para ver si hay errores, warning,... 
        <ul> SHELL
            <ol> tail -f /logs/laravel.log </ol>
        </ul>    
    </li>
</ul>


</p>
