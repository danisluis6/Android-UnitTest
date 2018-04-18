> - **Android-UnitTest**
>> - [Robolectric](#robolectric)
>> - [Espresso](#espresso)
>> - [References](#references)

    php --version 
    composer
    composer create-project laravel/laravel getting-started
    Alt + F12 (PHP Storm)
    php artisan serve
    
    Shiftx2 web.php
    Shiftx2 welcome.blade
    
# Robolectric
>>> - [Project setup](#project-setup) 
# Project setup
    
    testCompile "org.robolectric:robolectric:3.3.2"
    androidTestCompile 'junit:junit:4.12'
    


# Espresso
>>> - [Project setup](#project-setup) 

    - The best solution is to add untrusted server certificates automatically to android studio when using the internet from workplace. Go to Settings -> Tools -> Server Certificates, now check "Accept non-trusted certificates automatically". After this coding can be done offline.
    
    - testCompile 'junit:junit:4.12'
    androidTestCompile('com.android.support.test.espresso:espresso-core:2.2.2', {
        exclude group: 'com.android.support', module: 'support-annotations'
    })

# References
- Using Robolectric for Android unit testing on the JVM - Tutorial
http://www.vogella.com/tutorials/Robolectric/article.html

- 


