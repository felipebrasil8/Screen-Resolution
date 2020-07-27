# Screen Resolution

No mundo de hoje, há uma infinidade de dispositivos para as pessoas escolherem e pode ser assustador tentar acomodar e criar as melhores experiências em todos os dispositivos. No entanto, é importante manter-se atualizado com os tamanhos e resoluções de tela mais populares ao criar sites da Web e dispositivos móveis. Um site otimizado e responsivo facilita o fluxo do usuário e, por fim, uma experiência agradável para o seu público.

## Table of Contents

- [Viewports](#viewports)
-- [Measures](#measures)
- [References](#references)
- [Support](#support)
- [Contributing](#contributing)
- [Author](#author)

## Viewports

As viewports são versões reduzidas das resoluções que permitem que os sites sejam visualizados de maneira mais consistente em diferentes dispositivos. As viewports geralmente são mais padronizadas e menores que os tamanhos de resolução.

O QUE É O VIEWPORT?
Tamanho da janela de visualização para dispositivos
Hoje em dia, os Smart Phones têm uma resolução de tela muito alta. Um pequeno dispositivo de 6 polegadas possui as mesmas dimensões de tela que um LCD de 32 polegadas. Como é possível?

As dimensões do dispositivo, também conhecidas como resolução, são baseadas em pixels por polegada. Os dispositivos com resolução mais alta em tela pequena, seu ONE pixel contêm muito mais pixels, por isso a Tela Retina ou as Dimensões do dispositivo ficaram maiores. No entanto, as dimensões reais do dispositivo dependem dos pixels por polegada reais, chamados "Tamanho da janela de exibição" do dispositivo ou "largura do dispositivo". Sites responsivos Os estilos CSS são baseados nos tamanhos de dispositivos da Viewport.

### Measures to be tested

`0 ~ 575px` (sem media querie)<br>
`576 ~ 767px (sm)` [@media (max-width: 768px)]<br>
`768 ~ 991px (md)` [@media (max-width: 992px)]<br>
`992 ~ 1199px (lg)` [@media (max-width: 1200px)]<br>
`≥1200px (xl)` [@media (min-width: 1201px)]<br>

```css
/* 0 ~ 575px */
.classe {
    background-color: red;
}
/* 576 ~ 767px (sm, small) */
@media (max-width: 768px) {
    .classe {background-color: blue;
    }
}
/* 768 ~ 991px (md, medium) */
@media (max-width: 992px) {
    .classe {background-color: green;
    }
}
/* 992 ~ 1199px (lg, large) */
@media (max-width: 1200px) {
    .classe {background-color: yellow;
    }
}
/* >=1200px (xl, extra-large) */
@media (min-width: 1201px) {
    .classe {background-color: pink;
    }
}
```

### Helpers

Google Chrome `Device toolbar` measurements (Ctrl+Shift+M)

| Name | Size |
| :----: | :----: |
| Mobile S | 320 |
| Mobile M | 375 |
| Mobile L | 425 |
| Tablet | 768 |
| Laptop | 1024 |
| Laptop L | 1440 |
| 4K | 2560 |

Other measures

| Device | Viewport (px) |
| ------ | :-----: |
| iPhone 5/SE  | 320 |
| iPhone X     | 375 | 
| iPhone 11    | 414 |
| 13" Notebook | 1280 |
| 15" Notebook | 1366 |

### Example of CSS Media Queries

Apple iPhone 11 Media Queries

```css
@media only screen and (min-width: 414px) and (max-width: 767px) { /* Your Styles... */ }
```

## References

### Screen Size, Resolution, and Viewport...

[The best list with all `Devices` and their Details](https://yesviz.com/)

[More on `Viewport`](https://yesviz.com/viewport/)

[My screen resolution](https://pt.piliapp.com/what-is-my/screen-resolution/)

[Popular Screen Resolutions](https://mediag.com/blog/popular-screen-resolutions-designing-for-all/)

[Mobile First](https://blog.tecnospeed.com.br/mobile-first/)

### Screen Resolution Test

[Whatismyscreenresolution.net](http://whatismyscreenresolution.net/multi-screen-test)

[Material.io](https://material.io/resources/resizer/#device=window&width=1280)

[Cdeorama.com](http://www.codeorama.com/responsive/?u=uol.com.br)

[ResponsiveDesignChecker.com](https://www.responsivedesignchecker.com/checker.php)

### What is the world using?

[W3counter](https://www.w3counter.com/globalstats.php)

[Netmarketshare](https://netmarketshare.com/report.aspx?options=%7B%22filter%22%3A%7B%22%24and%22%3A%5B%7B%22deviceType%22%3A%7B%22%24in%22%3A%5B%22Desktop%2Flaptop%22%5D%7D%7D%5D%7D%2C%22dateLabel%22%3A%22Trend%22%2C%22attributes%22%3A%22share%22%2C%22group%22%3A%22browser%22%2C%22sort%22%3A%7B%22share%22%3A-1%7D%2C%22id%22%3A%22browsersDesktop%22%2C%22dateInterval%22%3A%22Monthly%22%2C%22dateStart%22%3A%222019-07%22%2C%22dateEnd%22%3A%222020-06%22%2C%22segments%22%3A%22-1000%22%2C%22plotKeys%22%3A%5B%7B%22browser%22%3A%22Chrome%22%7D%5D%7D)

## Support

Please [open an issue](https://github.com/felipebrasil8/readme-boilerplate/issues/new) for support.

## Contributing

Please contribute using [Github Flow](https://guides.github.com/introduction/flow/). Create a branch, add commits, and [open a pull request](https://github.com/felipebrasil8/readme-boilerplate/compare?expand=1).
Contributing

1. Fork it!
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -m 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request :D

## Author

| [![https://www.linkedin.com/in/felipe-brasil-5054b7177/](https://avatars3.githubusercontent.com/u/46094319?s=60&u=1f30318d54706b912da5a864fc8551e4d164a493&v=4)](https://www.linkedin.com/in/felipe-brasil-5054b7177/) |
| ----------------------------------------------------------------------------------------------------------------------------------------------- |
| [Felipe Brasil](https://www.linkedin.com/in/felipe-brasil-5054b7177/)                                                                                                |

© Felipe Brasil
