# Proyecto hoja de vida

Proyecto individual de página web de mi mi hoja de vida implementada a través de html y css con responsive de boostrap y métodos de Js.

## LENGUAJES

``` 
# Html

# JavaScript

# Css
```

## Edición:
``` 
# Lucas López Córtez


```

## License
[MIT](http://creativecommons.org/licenses/by/3.0/)
=======
# Proyecto Hoja de Vida

Proyecto programación IV: Hoja de vida usando HTML5, CSS3, RESPONSIVE DE BOOSTRAP 

## Instalación

Se enlaza con el HTML y el CSS, haciendo un llamado de las tecnologías como BOOSTRAp y JAVASCRIP 


## Usando

``` JavaScript
window.addEventListener('DOMContentLoaded', event => {

    // Activate Bootstrap scrollspy on the main nav element
    const sideNav = document.body.querySelector('#sideNav');
    if (sideNav) {
        new bootstrap.ScrollSpy(document.body, {
            target: '#sideNav',
            offset: 74,
        });
    };

    // Collapse responsive navbar when toggler is visible
    const navbarToggler = document.body.querySelector('.navbar-toggler');
    const responsiveNavItems = [].slice.call(
        document.querySelectorAll('#navbarResponsive .nav-link')
    );
    responsiveNavItems.map(function (responsiveNavItem) {
        responsiveNavItem.addEventListener('click', () => {
            if (window.getComputedStyle(navbarToggler).display !== 'none') {
                navbarToggler.click();
            }
        });
    });

});

```

## Integrantes

#####Lucas López Córtez


## License
[MIT](https://choosealicense.com/licenses/mit/)
Creative Commons Attribution 3.0 Unported
http://creativecommons.org/licenses/by/3.0/