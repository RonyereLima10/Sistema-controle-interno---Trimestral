# Sistema de Controle Interno - COREN-PB

Sistema web estático para análise trimestral das demonstrações contábeis e elaboração do parecer da Controladoria.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub.
2. Para disponibilizar o sistema a qualquer pessoa que tenha o endereço, deixe o repositório como **Public**.
3. Envie o arquivo `index.html` para a raiz do repositório.
4. No GitHub, abra **Settings → Pages**.
5. Em **Build and deployment**, selecione **Deploy from a branch**.
6. Selecione a branch `main` e a pasta `/ (root)`.
7. Clique em **Save**.
8. Aguarde a publicação. O GitHub apresentará o endereço do site, normalmente no formato:

   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## Funcionamento

O sistema funciona no navegador e não depende de banco de dados ou servidor para os cálculos. Os dados preenchidos são armazenados localmente no navegador por meio de `localStorage` e também podem ser exportados/importados em JSON pelos recursos disponíveis no próprio sistema.

## Atenção sobre os dados

Como o sistema armazena dados no navegador, o compartilhamento do endereço do site **não compartilha automaticamente os dados preenchidos por um usuário com outros usuários**. Cada navegador/dispositivo mantém seu próprio armazenamento local.

Não coloque no repositório arquivos contendo dados pessoais, informações financeiras sigilosas, credenciais, documentos internos ou outros dados que não devam ser públicos.

## Estrutura

- `index.html`: aplicação completa do sistema.
- `README.md`: instruções de publicação e funcionamento.

## Observação

A publicação no GitHub Pages disponibiliza a aplicação. A responsabilidade pela definição das permissões do repositório e pela escolha das informações que podem ser disponibilizadas publicamente é do responsável pela publicação.
