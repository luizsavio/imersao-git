# imersao-git

Tipos de CSS:
    1 - CSS externo (Arquivo .ccs linkado pelo link)
    2 - CSS Interno (Feito na tag Style dentro da tag Head)
    3 - Inline (Escrito direto no elemento Html na atributo style)

Hierarquia Que sobreescreve a escrita do outro:
    1 - Inline
        2 - CSS Interno
            3 - CSS externo
Ou seja, O CSS inline sempre vai sobreescrever  todos os outros, assim como o interno sobrepoe o externo;

---------------------------------------------------------------------------------------

Tipos de Seletores CSS:
    1 - Tag
    2 - Classe
    3 - Id
    4 - Atributos

Hierarquia que sobrepoe o outro:
    1 - Id
        2 - Atributos
            3 - Classe
                4 - Tag

Sempre o mais especifico sobrepoe o mais generico. Os atributos podem ser combinado, com seletores de tag.         


Rem - é relativo ao elemento pai HTML, se o font size no HTML tiver 18px e definirmos 1 Rem numa fonte o mesmo ira absorver 18px na pagina

Em - é relativo ao elemento pai. ex: div tem font size de 12px e dentro tem um h1 e se definirmos 1em para o h1 o mesmo assimira 12px na pagina

position:

Relative: é relativo aos outros elementos da pagina, se dermos um margin 10px, o elemento se afastata dos outros e nao ele que afasta os elementos;

Fixed: é atrelada ao viewport da pagina, independente se estiver dentro de outro elemento. Como é atrealdo ao VP o mesmo respeita o scroll

absolute: sempre respeita o elemento pai. Desde que o elemento pai seja definido como position relative, se nao ele vai respeitar o document. Porém nao vai respeitar o scroll.


