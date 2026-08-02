# NF-Auto — atualizações

Este repositório serve **apenas** para distribuir as atualizações do NF-Auto.
Não contém código-fonte.

## Como funciona

O arquivo `versao.json` diz qual é a versão atual. Cada cópia instalada do
NF-Auto consulta esse arquivo e, quando há versão nova, mostra no painel um
aviso com o botão **Atualizar agora**.

## Como publicar uma versão nova

1. Publique o `.zip` da versão nova em **Releases** deste repositório.
2. Edite o `versao.json` com o número novo, o link do zip e o que mudou.

Pronto — em até 1 hora todo mundo vê o aviso (ou na próxima vez que abrir).
