# LDAP

## Instalação

apk update

apk add samba rc- krb5


## Configuração

#### Criação das OUs vendedores e rh

[![OUldapVed](https://i.im.ge/2024/01/03/3MW4JY.OUldapVed.png)](https://im.ge/i/3MW4JY)

[![OUldapRH](https://i.im.ge/2024/01/04/3XpvVx.OUldapRH.png)](https://im.ge/i/3XpvVx)

#### Criação de grupos

[![grupsilva](https://i.im.ge/2024/01/04/3XpeMS.grupsilva.png)](https://im.ge/i/3XpeMS)



#### Movendo os grupos para as UOs

[![movGrupLdap](https://i.im.ge/2024/01/03/3MZGYa.movGrupLdap.png)](https://im.ge/i/3MZGYa)

[![OUrh](https://i.im.ge/2024/01/04/3Xp17T.OUrh.png)](https://im.ge/i/3Xp17T)



Incluir o(s) nome(s) e o conteúdo do(s) arquivo(s) de configuração.

- Criar duas OU: `vendedores` e `rh`;
- Mover o grupo `sobrenome1` e seus membros para a OU `vendedores`;
- Mover os grupo `sobrenome2` e seus membros para a OU `rh`.

## Teste


