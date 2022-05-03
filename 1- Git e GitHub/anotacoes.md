# Anotacoes importantes Git e GitHub

## Autenticacao

### Apontar para o git o repositorio remoto

- git remote add origin _link_

### Chave SSH

Na conta do GitHub acesse Settings -> SSH / GPG Keys

No terminal

- *comando* ssh-keygen -t ed25519 -C seu@email
- - escolher pasta se necessário

Acesse a pasta onde foi salva a chave

- *comando* cat id_ed25519.pub 
- copiar chave e add no github

Inicializar ssh

- *comando* eval $(ssh-agent -s)

- *comando ssh-add id_ed25519*
- digite a senha criada para a chave

- clone o repositorio remoto com o endereco SSH

## Enviando repositorio para Github

- git push origin master

*origin* é o alias dado ao repositorio ao apontar o diretorio remoto
*master* nome da branch

