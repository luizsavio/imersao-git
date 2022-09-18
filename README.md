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
