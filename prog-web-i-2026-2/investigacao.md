# Investigação de uma requisição real

1. Escolhi o site do IF Goiano (ifgoiano.edu.br) porque é o site da própria instituição onde estudo, então é fácil de acessar e relevante para o contexto da disciplina.

2. A página fez 67 requisições ao ser carregada (92.0 kB transferidos).

3. A primeira requisição, a do documento, foi feita com o método GET e retornou status 200 OK. A URL completa foi https://ifgoiano.edu.br/home/index.php.

4. Além do documento HTML, apareceram vários tipos de arquivo: imagens (png, jpeg, gif, svg+xml), scripts (script/js), folhas de estilo (css) e fontes (font).

5. Sim, apareceram requisições com status diferente de 200: duas com código 302 (vlibras-popup.jpg e vlibras-access.svg), que indicam redirecionamento para outro endereço, e três marcadas como "failed / net::ERR_BLOCKED" (vlibras-popup.jpg, vlibras-access.svg e supportedLanguages), que indicam que o navegador bloqueou o carregamento desses recursos, provavelmente por uma extensão ou política de bloqueio de conteúdo.

6. O endereço começa com https://. Isso significa que a conexão entre o navegador e o servidor é criptografada, então ninguém consegue interceptar e ler os dados que trafegam entre os dois.

7. O título principal da página usa o elemento `<h1>`, com a classe `portal-title-corto`, contendo o texto "Instituto Federal Goiano".

8. Ao reduzir a largura para cerca de 400 pixels, o menu de navegação (SUAP, Contato, Moodle, etc.) deixa de aparecer em linha horizontal e passa a ser acessado por um ícone de menu hambúrguer. O título da página também quebra em duas linhas, já que o espaço horizontal disponível diminuiu bastante.
