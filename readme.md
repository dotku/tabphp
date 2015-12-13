#TabPHP
It is a framework base on ThinkPHP 3.2, combined with AngularJS, BootStrap and Bower.  
  
## Modules
Usually, the modules are:  
1. Home, for default general browsing  
2. Profile, user's profile page  
3. Admin, for administration purpose  
  
## Config
1. Due to AngularJS, the default template engine of ThinkPHP must be turn off.  
2. For morden URL, we turn the SUFFIX to blank.  
3. I setup bootstrap as default theme in a folder, in case you want to customize the theme.  
  
        'URL_HTML_SUFFIX' =>'',
        'TMPL_ENGINE_TYPE' =>'PHP',
        'DEFAULT_THEME'    =>    'bootstrap'