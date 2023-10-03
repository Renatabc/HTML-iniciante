# HTML na prática

## Descrição
Um guia inicial com as principais tags e códigos envolvendo o HTML.

### Conceito de Tags
São palavras de "abertura" e "fechamento" que, colocadas nas partes correspondentes de uma estrutura de site, auxiliam não apenas na construção, como também na estilização, dinamismo, etc. Exemplos de algumas tags:<br><br>
```
<html></html>
<a></a>
<button></button>
```
O que cada uma significa e onde colocar cada uma delas veremos no decorrer desse artigo.

### Estrutura básica
Um site básico em HTML é composto de duas tags: HEAD e BODY e os elementos que estarão dentro de cada uma delas.

#### HEAD
Consiste em todos os dados que não serão mostrados, mas que são configurações importantes para o funcionamento do site. Exemplos:<br>
| Tags | Definição |
|-------|------------|
| title| Título que está na parte acima do link do site|

#### BODY
Consiste em tudo aquilo que estará a mostra ou faz parte dos itens visíveis em um site. Exemplos:<br>
| Tags | Definição |
|-------|------------|
| input| Campo para preencher respostas em formulários|
| img| Mostrar imagem|
|h1 até h6| Títulos e subtítulos|
|p| Texto simples, parágrafos|
|blockquote| Citação|

#### Atributos
Uma tag muitas vezes precisará de uma espécie de "extra", para facilitar tanto na edição e estilização, como em complementar determinado item um site. Os atributos estão escritos dentro das tags. Exemplo:<br>
```
<input type="password">
```
A tag input originalmente preenche um campo em texto, mas colocando o atributo type e especificando em seguida com password, eu o transformo em um campo para preencher senhas. Outros exemplos:<br>
| Atributos | Definição |
|-------|------------|
| id| Identifica uma tag, permitindo que apenas ela seja alterada conforme desejar|
| style | Permite alterar cor, fonte, tamanho, borda, etc|
|class| Ao contrário do id, posso nomear várias tags da mesma forma, permitindo que elas sofram as mesmas alterações|
|password| Inserção de senhas|
|number| Apenas inserção de números|
|color| Seletor de cor|
|text| padrão para inserção de texto|
|src| abreviatura de source, é um link tanto de site como de localização de pasta no computador, para imagens|
|width| Largura da imagem|
|height| Altura da imagem|
### Tags de estilização
| Tags | Definição |
|-------|------------|
| i| Deixa texto em itálico|
| strong | Deixa texto em negrito|
|u| Sublinhado|
|mark| marcador de texto|

#### Para saber mais
|Título| Definição| Link|
---------|--------|------
W3Schools| Um dicionário com as mais variadas linguagens| [Clique aqui](https://www.w3schools.com/html/default.asp)|