Formação Cybersecurity Specialist – Módulo 4
Exploração de Vulnerabilidades e Pós-Exploração

!Cybersecurity !Linux !Python !Metasploit !Status

Repositório destinado à documentação dos estudos, exercícios e desafios práticos desenvolvidos durante o Módulo 4 – Exploração de Vulnerabilidade e Pós-Exploração, do bootcamp Formação Cybersecurity Specialist, oferecido pela DIO.

O módulo aborda técnicas de exploração de vulnerabilidades, análise de sistemas comprometidos, escalonamento de privilégios, ataques Man in the Middle (MitM), mecanismos de persistência e simulação educacional de ransomware utilizando Python.

📚 Conteúdo do Módulo
4.1 Técnicas de Exploração de Vulnerabilidades
4.2 Pós-Exploração em Sistemas Comprometidos
4.3 Man in the Middle: Ataques e Mitigações
4.4 Desafio: Entendendo um Ransomware na Prática com Python
4.5 Materiais Complementares
4.6 Conclusão
🎯 Objetivo

O objetivo deste módulo foi aprofundar os conhecimentos sobre identificação, análise e exploração de vulnerabilidades em sistemas e redes, compreendendo como configurações inseguras, serviços expostos e falhas de segurança podem ser utilizados para comprometer ambientes computacionais.

Durante as atividades, foram estudadas ferramentas utilizadas em testes de intrusão, como Metasploit, Meterpreter, Nmap, Wireshark e Ettercap, além de conceitos relacionados à exploração de serviços, acesso remoto, escalonamento de privilégios, coleta de informações e persistência.

Também foram analisados ataques Man in the Middle e suas consequências para a confidencialidade e integridade das comunicações.

Por fim, foi desenvolvido um desafio prático utilizando Python para demonstrar, em ambiente controlado, o funcionamento básico da criptografia e descriptografia de arquivos, simulando a lógica de um ransomware.

Todas as atividades tiveram finalidade educacional, com execução em laboratório virtual e foco no entendimento dos riscos e das respectivas medidas de prevenção e mitigação.

🛠️ Tecnologias e Ferramentas Utilizadas
Sistemas Operacionais
Kali Linux
Windows 7
Windows XP
Windows 11
Linux
Virtualização
Oracle VM VirtualBox
VBoxManage
Segurança da Informação
Metasploit Framework
Metasploitable
Meterpreter
msfconsole
msfvenom
Damn Vulnerable Web Application (DVWA)
Ettercap
Wireshark
Nmap
Linguagens e Bibliotecas
Python
HTML
Markdown
Biblioteca os
Biblioteca pyaes
venv (ambientes virtuais Python)
Desenvolvimento e Versionamento
Visual Studio Code
Nano
Git
GitHub
Redes e Administração de Sistemas
ip
ifconfig
ipconfig
Task Manager
User Account Control (UAC)
📖 Desenvolvimento das Atividades
4.1 – Técnicas de Exploração de Vulnerabilidades

Nesta etapa, foram estudadas as principais técnicas de exploração de vulnerabilidades, considerando falhas em serviços de rede, problemas de autenticação, configurações inadequadas e mecanismos que podem permitir acesso não autorizado a sistemas.

Principais conceitos estudados

FTP (File Transfer Protocol)

Análise das fragilidades do protocolo FTP, incluindo autenticação anônima, transmissão de credenciais sem criptografia e possíveis falhas de configuração.

RDP (Remote Desktop Protocol)

Estudo dos riscos associados ao acesso remoto em sistemas Windows, incluindo exposição indevida do serviço, ataques contra autenticação e vulnerabilidades que podem comprometer a disponibilidade do sistema.

SSH (Secure Shell)

Análise do protocolo SSH, seus mecanismos de autenticação e a importância de utilizar chaves criptográficas, senhas fortes e controles de acesso.

Metasploit Framework

Estudo dos recursos do Metasploit para identificação e validação de vulnerabilidades em ambientes controlados.

Principais componentes:

msfconsole: interface principal do Metasploit.
msfvenom: ferramenta de geração e personalização de payloads.
Modules: módulos utilizados em atividades de exploração, reconhecimento e pós-exploração.
Payloads: códigos executados após a exploração de uma vulnerabilidade.

Meterpreter

Estudo do ambiente de interação remota do Metasploit e de suas funcionalidades para análise de sistemas, coleta de informações e avaliação de privilégios.

Backdoors

Compreensão dos mecanismos de acesso persistente não autorizado, seus riscos e formas de identificação e prevenção.

Atividades práticas realizadas

Foram desenvolvidos exercícios em máquinas virtuais utilizando Kali Linux, Metasploitable, Windows XP e Windows 7.

As atividades contemplaram:

Análise de vulnerabilidades relacionadas ao serviço FTP da máquina Metasploitable.
Estudo de vulnerabilidades associadas ao serviço RDP em ambiente Windows XP.
Avaliação de mecanismos de autenticação SSH em laboratório.
Demonstração controlada de comunicação reversa utilizando o Meterpreter em ambiente Windows 7.

Aprendizados:

Identificação de serviços vulneráveis.
Compreensão do funcionamento de exploits e payloads.
Análise de conexões remotas.
Reconhecimento dos riscos de backdoors.
Importância da atualização de sistemas e do controle de acesso.
4.2 – Pós-Exploração em Sistemas Comprometidos

Nesta etapa, foram estudadas as atividades realizadas após a obtenção de acesso a um sistema, com foco na compreensão dos impactos de um comprometimento e nos mecanismos utilizados para ampliar privilégios e coletar informações.

Principais conceitos estudados

Pós-exploração

Etapa que sucede a exploração inicial e envolve análise do sistema comprometido, identificação de usuários, processos, serviços e possíveis caminhos de escalonamento de privilégios.

Escalonamento de privilégios

Estudo das técnicas que permitem a um usuário com permissões limitadas obter privilégios superiores, como administrador ou SYSTEM no Windows.

Extração de informações

Análise dos riscos relacionados à exposição de arquivos, credenciais, informações de usuários e dados armazenados no sistema.

Persistência

Compreensão dos mecanismos que permitem a continuidade de acesso após reinicializações ou encerramento de processos.

Automação com scripts

Estudo da utilização de arquivos de configuração do Metasploit para automatizar tarefas de laboratório.

Atividades práticas realizadas

Utilizando a máquina virtual Windows 7 e o ambiente Kali Linux, foram explorados conceitos de:

Identificação de informações do sistema.
Verificação de usuários e privilégios.
Análise de processos em execução.
Estudo do funcionamento do UAC.
Avaliação de mecanismos de escalonamento de privilégios.
Análise de arquivos e informações armazenadas.
Transferência controlada de arquivos entre ambientes virtuais.
Utilização de módulos de reconhecimento do Metasploit.
Automação de configurações por meio de scripts .rc.
Estudo de mecanismos de persistência e seus riscos.

Aprendizados:

Importância do princípio do menor privilégio.
Riscos de permissões excessivas.
Necessidade de monitoramento de processos e sessões.
Identificação de comportamentos suspeitos.
Importância da auditoria de logs e da resposta a incidentes.
4.3 – Man in the Middle: Ataques e Mitigações

Nesta etapa, foram estudados os ataques Man in the Middle (MitM), nos quais um agente malicioso se posiciona entre duas partes que estão se comunicando, podendo interceptar ou modificar informações transmitidas.

Principais conceitos estudados

Man in the Middle (MitM)

Ataque que compromete a comunicação entre cliente e servidor, permitindo a interceptação de informações e, em determinadas situações, a manipulação do tráfego.

ARP (Address Resolution Protocol)

Protocolo responsável por relacionar endereços IP aos respectivos endereços MAC em uma rede local.

ARP Poisoning

Técnica de manipulação das tabelas ARP para redirecionar o tráfego de rede e possibilitar sua interceptação.

Sniffing

Processo de captura e análise de pacotes transmitidos pela rede.

Ferramentas utilizadas

Wireshark

Ferramenta utilizada para captura, inspeção e análise de pacotes de rede.

Ettercap

Ferramenta utilizada para estudar ataques MitM, análise de tráfego e manipulação de comunicações em ambientes controlados.

DVWA

Aplicação web vulnerável utilizada para demonstrar problemas de segurança em aplicações e analisar os riscos da transmissão de informações sem criptografia.

Atividades práticas realizadas

O laboratório foi desenvolvido utilizando Kali Linux, Metasploitable e Windows 7 no Oracle VM VirtualBox.

Foram realizadas atividades de:

Configuração da rede virtual Host-Only.
Acesso à aplicação DVWA.
Captura de pacotes utilizando Wireshark.
Análise de requisições HTTP.
Identificação de requisições GET e POST.
Estudo dos riscos de transmissão de credenciais em HTTP.
Análise do funcionamento do protocolo ARP.
Observação de tráfego interceptado em laboratório utilizando Ettercap.

Aprendizados:

Funcionamento da comunicação entre cliente e servidor.
Identificação de tráfego não criptografado.
Interpretação de pacotes de rede.
Riscos associados ao ARP Poisoning.
Importância do HTTPS e de certificados digitais.
Utilização de ferramentas para monitoramento e diagnóstico de redes.
Medidas de mitigação
Utilizar HTTPS com certificados válidos.
Evitar o envio de informações sensíveis em conexões HTTP.
Implementar mecanismos de proteção contra ARP Spoofing.
Utilizar redes segmentadas.
Monitorar alterações suspeitas nas tabelas ARP.
Implementar VPNs quando necessário.
Utilizar mecanismos de autenticação segura.
4.4 – Desafio: Entendendo um Ransomware na Prática com Python

Neste desafio, foi desenvolvido um projeto educacional para compreender o funcionamento básico de um ransomware por meio da criptografia e descriptografia de arquivos utilizando Python.

O objetivo foi demonstrar como um arquivo pode ter seu conteúdo transformado por um algoritmo criptográfico e posteriormente recuperado com a chave correspondente.

Tecnologias utilizadas
Python 3
Biblioteca os
Biblioteca pyaes
Algoritmo AES
Modo CTR
Ambiente virtual venv
Estrutura do projeto

O projeto foi organizado com três arquivos principais:

encrypter.py: responsável pela demonstração da criptografia do arquivo.
decrypter.py: responsável pela recuperação do conteúdo original.
teste.txt: arquivo utilizado como conteúdo de teste.
Funcionamento

O processo foi dividido em duas etapas:

1. Criptografia

O primeiro script realiza a leitura do arquivo de teste e utiliza o algoritmo AES no modo CTR para transformar seu conteúdo em dados criptografados.

2. Descriptografia

O segundo script utiliza a mesma chave criptográfica para recuperar o conteúdo original do arquivo.

O exercício demonstra a importância do gerenciamento seguro de chaves e os riscos associados ao uso malicioso da criptografia.

Organização do ambiente Python

Foi utilizado um ambiente virtual para isolar as dependências do projeto.

A biblioteca pyaes foi instalada nesse ambiente, evitando alterações nas bibliotecas globais do sistema operacional.

Aprendizados
Manipulação de arquivos com Python.
Leitura e gravação de dados binários.
Conceitos de criptografia simétrica.
Funcionamento do algoritmo AES.
Utilização do modo CTR.
Gerenciamento de dependências Python.
Criação e utilização de ambientes virtuais.
Compreensão do funcionamento básico de ransomware.
Importância de backups e estratégias de recuperação de dados.

Observação de segurança: o projeto possui finalidade exclusivamente educacional e deve ser executado somente com arquivos de teste em ambientes controlados.

4.5 – Materiais Complementares

Durante o módulo, foram utilizados materiais de apoio e ferramentas para aprofundar os conhecimentos sobre exploração de vulnerabilidades, análise de tráfego e segurança de sistemas.

Referências e ferramentas
Metasploit Framework
Kali Linux
Wireshark
Ettercap
Python
Documentação oficial do Python
Damn Vulnerable Web Application
VirtualBox
GitHub
4.6 – Conclusão

O Módulo 4 proporcionou uma visão prática sobre técnicas de exploração de vulnerabilidades e atividades de pós-exploração, permitindo compreender como falhas de configuração, serviços desatualizados e mecanismos inadequados de autenticação podem comprometer a segurança de sistemas e redes.

As atividades realizadas contribuíram para o desenvolvimento de conhecimentos sobre utilização de ferramentas como Metasploit, Meterpreter, Wireshark e Ettercap, além de proporcionar uma compreensão mais aprofundada dos ataques Man in the Middle, escalonamento de privilégios e persistência.

O desafio desenvolvido em Python também permitiu explorar conceitos fundamentais de criptografia simétrica e compreender o funcionamento básico de um ransomware.

De maneira geral, os conhecimentos adquiridos reforçaram a importância da identificação de vulnerabilidades, aplicação de atualizações, monitoramento contínuo, proteção de credenciais, segmentação de redes e implementação de boas práticas de segurança.

Este módulo contribuiu para fortalecer minha base técnica em Cybersecurity, especialmente nas áreas de Vulnerability Assessment, Penetration Testing, Network Security e Incident Response.

📂 Estrutura do Repositório
text
boot_036/
│
├── README.md
│
├── dp_ransomware/
│   ├── encrypter.py
│   ├── decrypter.py
│   └── teste.txt
│
└── meterpreter.rc

Descrição dos arquivos
Arquivo	Descrição
README.md	Documentação do módulo e das atividades desenvolvidas.
dp_ransomware/	Diretório do desafio prático de ransomware.
encrypter.py	Script educacional de criptografia.
decrypter.py	Script educacional de descriptografia.
teste.txt	Arquivo de texto utilizado nos testes.
meterpreter.rc	Arquivo de configuração utilizado no laboratório para automatização do ambiente de testes.
⚖️ Aviso Legal

Todo o conteúdo deste repositório possui finalidade educacional e foi desenvolvido no contexto de estudos em segurança da informação.

As técnicas e ferramentas apresentadas devem ser utilizadas exclusivamente em ambientes próprios, virtuais ou devidamente autorizados.

Não utilize os conhecimentos apresentados para acessar sistemas sem autorização, capturar informações de terceiros ou comprometer redes e dispositivos.

Conhecimento em segurança cibernética exige responsabilidade, ética e respeito aos limites legais.

