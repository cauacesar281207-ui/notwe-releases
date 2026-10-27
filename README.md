# Notwe — instaladores

Este repositório contém **apenas** os instaladores assinados do app desktop
do Notwe (Windows) e o arquivo `latest.json` usado pela atualização automática.
**Não há código-fonte aqui.**

- Cada release traz o instalador `.exe`, a assinatura `.sig` e o `latest.json`.
- O app só instala uma atualização se a assinatura bater com a chave pública
  embutida nele; um instalador alterado é recusado.
- O app em si é só uma janela segura para o Notwe: todo o conteúdo é cifrado
  de ponta a ponta nos aparelhos dos usuários.
