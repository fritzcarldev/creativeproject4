# creativeproject4

## Index.html (Bootstrap link, and google font link)
```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<link href='https://fonts.googleapis.com/css?family=Montserrat' rel='stylesheet'>
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>

```

## Components
1. AboutSection
2. ComingSoon
3. FooterSection
4. ImageGrid
5. PostComponent
6. SlideShow
7. TeamInfo

## Axios
1. Used to make HTTP requests from Node.js
2. PostService.js used to make requests, GET, CREATE, DELETE requests

## Installation -> for slide on welcome page
``` npm install vueperslides ```
``` https://antoniandre.github.io/vueper-slides/``` for documentation

## CSS

``` 
<style>
body {
    font-family: 'Montserrat', Arial, Helvetica, sans-serif;
}
/* Menu */
.bg-dark {
    background-color: #3B848C !important;
  }

  .navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
    color: #F2B56B;
  }
  
  .navbar-dark .navbar-nav .nav-link {
    color: #ffffff;
    font-weight: normal;
  }

  .navbar-nav {
      display: flex;
      justify-content: center;
  }

  .header-container {
    color: #3b3b3b;
    background-color: #3B848C;
    display: flex;
    justify-content: center;
  }
  
  .header {
    display: flex;
    justify-content: center;
  }

  /* .navbar-nav > li{
    padding-left:40px;
    padding-right:40px;
  } */
  #app .nav-link {
  padding-left: 40px;
  padding-right: 40px;
  text-align: center;
  font-weight: normal;
}

  
</style>

```





# client

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

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
