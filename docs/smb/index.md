# SMB

## Instalação
Comando para atualizar o catalogo:

apk update

<<<<<<< HEAD
Comando para instalar o servidor samba:

apk add samba-dc krb5

[![instsamba](https://i.im.ge/2024/01/03/3MEXaK.instsamba.png)](https://im.ge/i/3MEXaK)

## Configuração


Comando para configurar o samba:

nano /etc/samba/smb.conf

### Tela de configuração

[![criandopasta](https://i.im.ge/2024/01/04/3XVQCG.criandopasta.png)](https://im.ge/i/3XVQCG)


[![instsamba](https://i.im.ge/2024/01/03/3MEXaK.instsamba.png)](https://im.ge/i/3MEXaK)

#### Criação de  OUs usuario AD Windows

[![criaçãoOUs](https://i.im.ge/2024/01/03/3M3BZf.criacaoOUs.png)](https://im.ge/i/3M3BZf)

[![criaçãoOUL](https://i.im.ge/2024/01/03/3MYrpL.criacaoOUL.png)](https://im.ge/i/3MYrpL)

[![CriaUsuSilva](https://i.im.ge/2024/01/03/3M3stp.CriaUsuSilva.png)](https://im.ge/i/3M3stp)

[![criaUsuL](https://i.im.ge/2024/01/03/3M3azP.criaUsuL.png)](https://im.ge/i/3M3azP)

[![addGsilva](https://i.im.ge/2024/01/03/3M3ChS.addGsilva.png)](https://im.ge/i/3M3ChS)

[![addGlimaO](https://i.im.ge/2024/01/03/3M3byK.addGlimaO.png)](https://im.ge/i/3M3byK)


#### Pastas compartilhadas

[![pastascompar](https://i.im.ge/2024/01/04/3XKUGL.pastascompar.png)](https://im.ge/i/3XKUGL)

#### Usuario com acesso negado

[![negacessopasta](https://i.im.ge/2024/01/04/3XK5pa.negacessopasta.png)](https://im.ge/i/3XK5pa)



=======
apk add samba-dc krb5

## Configuração

nano /etc/samba/smb.conf

>>>>>>> fc1c8ed26f87975a2793b6cf562f4fa7af61f6db
Incluir o(s) nome(s) e o conteúdo do(s) arquivo(s) de configuração.

1. Criar 2 grupos para dois de seus sobrenomes;
[![criaçãodeusuario](https://i.im.ge/2023/12/30/xgBvyJ.criacaodeusuario.png)](https://im.ge/i/xgBvyJ)
2. Criar 4 usuários, dois para cada um dos sobrenomes;
   
3. Compartilhar duas pastas com dois de seus sobrenome, compartilhado para o grupo com o sobrenome correspondente.

## Teste


