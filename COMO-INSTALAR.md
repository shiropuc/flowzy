# Como instalar o Flowzy (para quem recebeu o convite)

Você vai precisar de: um PC com Windows 10 ou 11 (64 bits), o arquivo **Flowzy-Setup-X.Y.Z.exe** e o **código de convite** (`XXXX-XXXX`) que o dono do servidor te mandou.

## 1. Abrir o instalador
Dê dois cliques em **Flowzy-Setup-X.Y.Z.exe**.

O Windows provavelmente vai mostrar uma tela azul: **"O Windows protegeu o computador"**. Ela aparece porque o Flowzy é um programa novo e ainda não tem um certificado pago de "editora conhecida". Não quer dizer que tem vírus.
1. Clique em **Mais informações** (texto pequeno, embaixo da mensagem).
2. Confira que aparece **Aplicativo: Flowzy-Setup-…exe**.
3. Clique em **Executar assim mesmo**.

> Só faça isso com o instalador que o dono do servidor te mandou (ou que o próprio Flowzy baixou ao se atualizar).

## 2. Instalar
Clique em **Instalar** e espere. O Flowzy é instalado só para o seu usuário do Windows; não precisa ser administrador.

No meio da instalação o Windows pergunta **"Deseja permitir que este aplicativo faça alterações no seu dispositivo?"** — o programa é o **driver de controle ViGEmBus**, da **Nefarius Software Solutions** (assinado digitalmente). Ele permite usar controle de videogame no "Jogar junto".
- Clique em **Sim** para instalar o driver (recomendado).
- Se clicar em **Não**, o Flowzy funciona normalmente; só o controle no "Jogar junto" fica desligado.

No fim, o Flowzy cria um atalho na **Área de Trabalho** e no **Menu Iniciar**.

## 3. Primeira vez que abrir
1. Escolha seu **nome de usuário**.
2. O campo **Servidor** já vem preenchido — não mexa.
3. Clique em **Entrar**. Vai aparecer o campo **Código**: digite o convite (`XXXX-XXXX`) e clique em **Entrar** de novo.
   O convite vale **uma vez só** e por **7 dias**. Depois disso, o seu PC fica lembrado e entra sozinho.

## 4. Avisos do Firewall (Segurança do Windows)
Na primeira vez que você usar **voz**, **compartilhar a tela** ou o **Jogar junto**, o Windows pode perguntar se o **Flowzy** (ou o **sunshine**, que é o motor de jogo do Flowzy) pode usar a rede.
- Marque **Redes privadas** e clique em **Permitir acesso**.
- Sem isso, o "Jogar junto" pela internet pode não conectar.

## 5. Atualizações
Quando sair uma versão nova, aparece um aviso amarelo embaixo: **"Nova versão disponível · Atualizar agora"**.
- Clique quando quiser. O Flowzy confere a **assinatura digital** da versão antes de instalar — uma versão falsa é recusada.
- O programa fecha e abre de novo sozinho em alguns segundos.

## Problemas comuns
- **"Para entrar, você precisa de um código de convite"**: peça um convite novo ao dono (o seu pode ter vencido ou já ter sido usado).
- **"Esse nome já pertence a um membro"**: escolha outro nome. Se o nome é seu e você trocou de PC, use, no aparelho antigo, **Configurações → Minha conta → Conectar outro aparelho**.
- **O jogo não abre pela internet**: confira o passo 4 (Firewall) nos dois PCs.

## Desinstalar
**Configurações do Windows → Aplicativos → Flowzy → Desinstalar.** O driver do controle continua instalado (outros programas podem usar); para tirar, desinstale **ViGEmBus** na mesma lista.
