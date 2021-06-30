# medipresent

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Project's SRC structure 

* Router used in src/router/ [ Routes structure ]
* Store used in src/store/ [ Global state ]
* Store used in src/constants/ [ Global constants used accross the App ]
* Store used in src/components/ [ Basic component blocks used in vue] 
* Store used in src/styles/ [ SCSS files ]
* Store used in src/views/ [ Main app Content views ]
* ./app
* ./main

Template Layout in src/Layouts 

 ___Components___  

 __Dashboard__
 ```
 * ./NavBar 
 * ./SideNav
 * ./BottomBar

 ```
  __Homepage__
 ```
 * ./NavBar 
 * ./SideNav (Mobile)

 ```

 ### Layout structure in tabular demo
  ```
           Navbar
  ```


  ***SideNav*** |  ***Content***
  ---  | ---
   (Desktop Only)   | (App Content)

```
  Bottom Bar (Mobile Only)
```





### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
