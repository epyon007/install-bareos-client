# install-bareos-client

Esta playbook realiza a instalação do cliente do Bareos para execução de backups, caso você tenha a intenção de executar esta playbook em seu ambiente, pode ser interessante editar os arquivos/parametros a seguir para a as necessidades do seu ambiente:

- **./inventory/hosts**  - **Endereços IP das respectivas máquinas a receberem a instalação do client Bareos**
- **./vars/main.yml** - **Neste arquivos são checadas as variaveis utilizadas na playbook**
- **./templates/** - **Arquivo que define os padrões a serem seguidos nos arquivos de configuração da aplicação.**
- **playbook.yml** - **Especialmente o campo "hosts" caso queira replicar o ambiente em máquinas virtuais.**

- [x] Working in Debian and Ubuntu
- [x] Working in CentOS and redhat
