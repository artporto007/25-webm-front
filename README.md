# 25-webm-front

Projeto front-end simples que fornece páginas HTML e CSS para gerenciar questões e usuários, com integração de upload de arquivos via Uploadcare.

## Estrutura do projeto

- [index.html](index.html)  
  Página inicial com botão para buscar informações (ex: autor, API, BD).

- [questoes.html](questoes.html)  
  Dashboard de questões. Lista as questões e permite navegar para inserir/editar.

- [inserir-questao.html](inserir-questao.html)  
  Formulário para inserir nova questão (enunciado, disciplina, tema, nível e imagem via Uploadcare).

- [ver-questao.html](ver-questao.html)  
  Página de edição/visualização de uma questão existente (formulário semelhante ao de inserção).

- [usuarios.html](usuarios.html)  
  Dashboard de usuários. Lista usuários com ações (editar/excluir) e botão para inserir.

- [inserir-usuario.html](inserir-usuario.html)  
  Formulário para inserir novo usuário (nome, e-mail, senha e imagem via Uploadcare).

- [ver-usuario.html](ver-usuario.html)  
  Página de edição/visualização de um usuário existente (formulário para atualizar dados e imagem).

- [css/estilo.css](css/estilo.css)  
  Estilos principais do projeto (layout, formulários, botões e tabela).

- [README.md](README.md)  
  Arquivo atual com descrição do projeto e da estrutura (este arquivo).

## Observações

- Os formulários usam componentes do Uploadcare (pubkey pública presente nos HTMLs) para upload de imagens.
- Para executar localmente: abrir `index.html` no navegador.
