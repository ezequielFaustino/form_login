# HTML references

-  `<html>` representa a raiz de um documento HTML ou XHTML. Todos os elementos devem ser descendentes desse elemento;
-  `<!DOCTYPE html>` o doctype é a introdução encontrada no topo de todos os documentos. Seu único propósito é evitar que o browser mude para os chamados "quirks mode" quando renderizar um documento; isto é o doctype garante que o browser faça um esforço na tentativa de seguir as especificações relevantes, em vez de usar um modo de renderização diferente e que seja incompatível com algumas especificações;
-  `<html lang="pt-br">` o atributo global lang ajuda a definir o idioma de um elemento;
- `<head>` providencia informações gerais (metadados) sobre o documento, incluindo seu título e links para scripts e folhas de estilos;
- - ` <meta charset="UTF-8">` Este atributo define a codificação de caracteres usada na página.
- - ` <meta http-equiv="X-UA-Compatible" content="IE=edge">`: oferece suporte a navegadores legados antigos.
- - ` <meta name="viewport" content="width=device-width, initial-scale=1.0">`: meta-tag comumente usado em web design responsivo.
- - `<title>` define o título do documento, mostrando na barra de título de uma navegador ou na aba da página.
- - `<link rel="stylesheet" href="css/styles.css">` especifica as relações entre o documento atual e um recurso externo. Possíveis usos para este elemento incluem a definição de uma estrutura relacional para navegação. Este elemento é mais usado para vincular as folhas de estilo. o atributo _rel_ especifica a relação entre o atual documento e o documento/arquivo referenciado.
- `<body>` representa o conteúdo de um documento HTML. è permitido apenas um <body> por documento.
- - `<main>` define o conteúdo principal dentro do <body> em seu documento ou aplicação. Entende-se como conteúdo principal aquele relacionado diretamente com o tópico central da página ou com a funcionalidade central da aplicação. O mesmo deverá ser único na página, ou seja, dentro do elemento <main> não deverão ser incluidas seções da página que sejam comuns a todo o site ou aplicação, tais como mecanismos de navegação, informações de copyright, logotipo e campos de busca (a não ser, é claro, caso a função principal do documento seja fazer algum tipo de busca).
- - `<section>` representa uma seção genérica contida em um documento HTML, geralmente com um título, quando não existir um elemento semântico mais específico para representá-lo.
- - `<div>` é um container genérico para conteúdo de fluxo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos (usando class ou id), ou porque eles compartilham valores de atributos, como lang. 
