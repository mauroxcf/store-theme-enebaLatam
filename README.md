# Tienda Eneba Latam

## Preview

![image](https://user-images.githubusercontent.com/66022141/209351550-a1f116a7-8944-4134-aad7-173f489335cd.png)

## Configuración

### Paso 1 - Configuración básica

- Seguir la siguiente guía para instalar el VTEX CLI [link](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-vtex-io-cli-install)

- ingresar a vtex con tu cuenta de usuario con el siguiente comando:

```
vtex login {account-name}
```

### Paso 2 - Clonación de repositorio

- puedes clonar este repositorio en tu maquina local con el siguiente comando en tu terminal:

```
git clone https://github.com/mauroxcf/store-theme-enebaLatam.git
```

### Paso 3 - Editar el Manifest.json

- en el manifest hay un par de valores que toca editar según la cuenta de partner con la que te hayas logueado, que serian:
  `"vendor": "nombre_del_partner"`
  `"name": "nombre_de_la_tienda"`

### Paso 4 - Instalar apps necesarias

- para instalar aplicaciones necesarias puede usar los comandos siguientes, dependiendo si tiene el nombre o no de la dependencia:

```
vtex install vtex.store-theme@0.0.1
```

o

```
vtex install nombre_de_app
```

### Paso 5 - Desinstalar el store-theme predeterminado

- si ha seguido las indicaciones hasta el momento, es posible que tenga el tema de la tienda instalado, para desinstalarlo, ejecute el siguiente comando:

```
vtex uninstall vtex.store-theme@0.0.1
```

### Paso 6 - Ejecute un preview de la tienda

- por ultimo ya con todo instalado en su ambiente, puede ejecutar el siguiente comando para visualizar la tienda en su navegador, si en la consola no arroja errores, debería de mostrarla sin ningún problema:

```
vtex link
```

## Dependencies

1. Store-theme

## Store Component Apps

1. "vtex.store"
2. "vtex.store-header"
3. "vtex.product-summary"
4. "vtex.store-footer"
5. "vtex.store-components"
6. "vtex.styleguide"
7. "vtex.slider"
8. "vtex.carousel"
9. "vtex.shelf"
10. "vtex.menu"
11. "vtex.minicart"
12. "vtex.product-details"
13. "vtex.product-kit"
14. "vtex.search-result"
15. "vtex.login"
16. "vtex.my-account"
17. "vtex.flex-layout"
18. "vtex.rich-text"
19. "vtex.store-drawer"
20. "vtex.locale-switcher"
21. "vtex.product-quantity"
22. "vtex.product-identifier"
23. "vtex.product-specification-badges"
24. "vtex.product-review-interfaces"
25. "vtex.telemarketing"
26. "vtex.order-placed"
27. "vtex.stack-layout"
28. "vtex.tab-layout"
29. "vtex.responsive-layout"
30. "vtex.slider-layout"
31. "vtex.iframe"
32. "vtex.breadcrumb"
33. "vtex.sticky-layout"
34. "vtex.add-to-cart-button"
35. "vtex.store-link"
36. "vtex.search"
37. "vtex.product-price"
38. "vtex.store-icons"
39. "vtex.product-list"
40. "vtex.checkout-summary"
41. "vtex.modal-layout"
42. "itgloberspartnercl.whatsapp-button"
43. "itgloberspartnercl.bullets-diagramation"
44. "itgloberspartnercl.add-to-cart-info"

## Custom Apps

1. [add-to-cart-info](https://github.com/mauroxcf/itgloberspartnercl-add-to-cart-info)
2. [bullets-diagramation](https://github.com/mauroxcf/itgloberspartnercl-bullets-diagramation)
3. [whatsapp-button](https://github.com/mauroxcf/itgloberspartnercl-whatsapp-button/tree/feature-whatsapp-custom-app)

## Autors ✒️

Mauricio Contreras - [Github :octocat:](https://github.com/mauroxcf) - [Twitter](https://twitter.com/MauroJCF) - [Linkedin](https://www.linkedin.com/in/mauricio-contrerasf/)
