# Criação de usuários no Linux
Este repositório contém um script de shell simples para automatizar a criação de usuários no ambiente Linux. O script também inclui a configuração de grupos de usuários, diretórios e permissões, tornando-o útil para a preparação de novas máquinas virtuais


## Uso

1 - Clone este repositório:

git clone https://github.com/Nayumt99/useradd-linux/ 
cd seu-repositorio

2 - Dê permissões de execução ao script:

chmod +x setup_infra.sh

3 - Faça upload do script no GitHub:

Crie um repositório no GitHub.
Adicione e confirme o script:

git init
git add setup_infra.sh
git commit -m "Adicionando script de configuração de infraestrutura"
git remote add origin https://github.com/Nayumt99/useradd-linux.git
git push -u origin master


Ao iniciar uma nova máquina virtual, você pode clonar o repositório do GitHub e executar o script:

git clone https://github.com/Nayumt99/useradd-linux.git
cd seu-repositorio
./setup_infra.sh


## Detalhes do Script

* Criação de Usuários:
O script utiliza o comando useradd para criar usuários no sistema.

* Criação de Grupos de Usuários:
Utiliza o comando groupadd para criar grupos de usuários.

* Atribuição de Usuários aos Grupos:
Usa o comando usermod para adicionar usuários aos grupos correspondentes.

* Criação de Diretórios:
Utiliza o comando mkdir para criar diretórios específicos para cada usuário.

* Atribuição de Permissões:
Utiliza chown e chmod para atribuir permissões adequadas aos diretórios.


## Personalização

Adapte o script de acordo com as necessidades específicas do seu ambiente. Adicione ou remova comandos conforme necessário para atender aos requisitos de configuração do seu sistema.


## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para sugerir melhorias, correções ou novos recursos por meio de issues ou pull requests.

## Materiais de apoio

:brazil: [Guia Linux}(https://guialinux.uniriotec.br/)

:brazil: [Curso Linux Dio](https://web.dio.me/)

## Aviso

Tenha cuidado ao lidar com senhas ou informações sensíveis. Este script é um exemplo básico e pode precisar de ajustes adicionais para ambientes mais complexos ou seguros.

