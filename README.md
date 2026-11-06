# Flowzy

Chat, voz, compartilhamento de tela e "Jogar junto" (jogo remoto) entre amigos — em preto e amarelo.

Este repositório guarda **somente as versões do programa** (instaladores para Windows) e as licenças.
O Flowzy é de uso por convite: sem um código de convite do dono do servidor, não dá para entrar.

## Baixar
Vá em **[Releases](../../releases/latest)** e baixe `Flowzy-Setup-X.Y.Z.exe`.
Como instalar (avisos do Windows, driver do controle, primeiro acesso): veja [COMO-INSTALAR.md](COMO-INSTALAR.md).

## Atualizações e segurança
O programa procura versões novas aqui e avisa "Nova versão disponível". Antes de instalar, ele confere a
**assinatura digital** (Ed25519) do arquivo `flowzy-update.json` de cada versão com a chave pública embutida no
programa, além do tamanho e do SHA-512 do instalador. Uma versão sem a assinatura do dono é recusada.

## Licenças de terceiros
O Flowzy inclui o **Sunshine** (modificado) e o **Moonlight**, ambos sob a **GNU GPL v3.0**, e o driver
**ViGEmBus** (BSD 3-Clause). Detalhes em [licencas/TERCEIROS.txt](licencas/TERCEIROS.txt).
A modificação feita no Sunshine está em [licencas/sunshine-flowzy.patch](licencas/sunshine-flowzy.patch)
(aplicada sobre o Sunshine v2026.914.233613: https://github.com/LizardByte/Sunshine). Os mesmos arquivos vão
dentro do programa instalado, na pasta `resources\licencas`.
