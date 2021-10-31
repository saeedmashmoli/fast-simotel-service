# fast-simotel-service



<!-- ABOUT THE PROJECT -->
## About The Project
this library created for fast simotel services

## Install Library
```sh
composer require fast-service/fast-simotel-service
```



## Usage

1.Create and set enviroment variable `.env` file
```sh
API_BASE_URL=<YourSimotelApiUrl>           //example https://0.0.0.0/api/v3/autodialer/
API_KEY=<YourSimotelApiToken>              //show or create in simotel admin panel maintenance -> api accounts 
API_USERNAME=<YourSimotelApiUsername>      //show or create in simotel admin panel maintenance -> api accounts
API_PASSWORD=<YourSimotelApiPassword>      //show or create in simotel admin panel maintenance -> api accounts
```

2.Use Class FastSimotelService in your controller
```sh
<?php
require_once './vendor/autoload.php';
use FastSimotelService\FastSimotelService;

FastSimotelService::run_fast_campaign();
```
3. Send post request to your controller that use FastSimotelService
 
 
