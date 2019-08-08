PDO PHP Database Object composer install namespace

1) composer install

2) Add code in composer.json

"autoload": {

        "psr-4": {
            "App\\": "",
            "PDO\\": "PDO"
        },
        "files": [
            "config.php"
        ]
    }
    
    
3) root-directory it is namespace App;

namespace PDO = folder /PDO/