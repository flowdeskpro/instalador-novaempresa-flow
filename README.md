## CRIAR SUBDOMINIO E APONTAR PARA O IP DA SUA VPS

Testado ubuntu 20 e 22


Editar arquivo config e colocar senhas de sua preferencia e seu email, dominios.

Se quiser instalar 2 instancia mudar nome da instancia, porta backend, porta frontend e porta_postgre_intancia, não deve utilizar mesmas portas de outras instalações

A opção atualizar vai pegar ultima versao do repositorio usado para instalar

Nunca usar portas 80 e 443 para backend utilize porta 3000 a 3100 e frontend 4000 a 4100


# FAZENDO DOWNLOAD DO INSTALADOR & INICIANDO A PRIMEIRA INSTALAÇÃO (USAR SOMENTE PARA PRIMEIRA INSTALAÇÃO):

```bash
sudo apt install -y git && git clone https://github.com/flowdeskpro/instalador-novaempresa-flow.git  install && sudo chmod -R 777 install  && cd install  && sudo ./install_primaria
```


# ACESSANDO DIRETORIO DO INSTALADOR & INICIANDO INSTALAÇÕES ADICIONAIS (USAR ESTE COMANDO PARA SEGUNDA OU MAIS INSTALAÇÃO:

```bash
cd ./install  && sudo ./install_instancia
```
 
 
