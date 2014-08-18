CSScomb-Configuration
=====================

Contains the configuration file for CSS Comb to refactor CSS &amp; SCSS beautifully.

## Make this 

```scss
/** * * Home * **/ 
.page-home {article {padding : 15px 15px 0; h1 {font-family : $Openregular; font-weight : normal; display : inline; } 
h2, .subtitle {font-family : $Openbold; font-size : 14px; font-weight : normal; display : inline; color : #999999; } } } 
.home-placeholder {position : relative; margin : 30px 1px; img {max-width : 100%; height : auto; } } 
.home-text {font-family : $Openbold; font-size : 20px; left: 50%; margin-left: -200px; position : absolute; top : 319px; width : 100%; text-align : center; text-transform : uppercase; }
```


## Become this

```scss
/**
*
* Home
*
**/

.page-home {
    article {
        padding : 15px 15px 0;
        h1 {
            font-family : $Openregular;
            font-weight : normal;
            display : inline;
        }
        h2, .subtitle {
            font-family : $Openbold;
            font-size : 14px;
            font-weight : normal;
            display : inline;
            color : #999999;
        }
    }
}

.home-placeholder {
    position : relative;
    margin : 30px 1px;
    img {
        max-width : 100%;
        height : auto;
    }
}

.home-text {
    font-family : $Openbold;
    font-size : 20px;
    position : absolute;
    top : 319px;
    width : 100%;
    text-align : center;
    text-transform : uppercase;
}
```
