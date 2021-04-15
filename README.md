
## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

## About Package
   This package is a sample for creating laravel package, to make it easy for the development of large size project. As we now, packages are independent modules which performs a specific task. I created this project, to get understand the flow, for creating laravel packages.


## Installation

    For using custom package
    
1. Hit the command, after navigating to project directory.
    Composer require globalgarner/samplepackage
    
3. Add following lines 

	" GlobalGarner\Samplepackage\SampleProjectServiceProvider::class "
	
	To the config/app.php file, in providers array
	
3. Then hit the following command
        php artisan vendor:publish
        
    Then you would be asked to a number next to SampleProjectServiceProvider, enter that number, and press `Enter`
    
5. Open project in browser, and go to path '/sample', you would see the text 'hii my tester'.


