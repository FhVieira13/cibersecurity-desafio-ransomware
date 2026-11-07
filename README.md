# 🛡️ Formação Cybersecurity Specialist – Módulo 4
## Exploração de Vulnerabilidades e Pós-Exploração

<p align="center">
  <img src="https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge&logo=git" alt="Status Concluído">
  <img src="https://img.shields.io/badge/Cybersecurity-Specialist-blue?style=for-the-badge&logo=kalilinux" alt="Cybersecurity">
  <img src="https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Metasploit-Framework-red?style=for-the-badge" alt="Metasploit">
</p>

Repositório destinado à documentação dos estudos, exercícios práticos e desafios desenvolvidos durante o **Módulo 4 – Exploração de Vulnerabilidade e Pós-Exploração** do bootcamp *Formação Cybersecurity Specialist*, oferecido pela **DIO**.

O módulo aborda técnicas avançadas de exploração, análise de sistemas comprometidos, escalonamento de privilégios, ataques *Man in the Middle* (MitM), mecanismos de persistência e a simulação educacional de um ransomware utilizando Python.

---

## 📑 Conteúdo do Módulo

*   **4.1** 🚀 Técnicas de Exploração de Vulnerabilidades
*   **4.2** 🕵️‍♂️ Pós-Exploração em Sistemas Comprometidos
*   **4.3** 🌐 Man in the Middle: Ataques e Mitigações
*   **4.4** 💻 Desafio: Entendendo um Ransomware na Prática com Python
*   **4.5** 📚 Materiais Complementares
*   **4.6** 🎓 Conclusão

---

## 🎯 Objetivo

O objetivo deste módulo foi aprofundar os conhecimentos sobre identificação, análise e exploração de vulnerabilidades em sistemas e redes, compreendendo como configurações inseguras, serviços expostos e falhas de segurança podem ser utilizados para comprometer ambientes computacionais.

Durante as atividades, foram estudadas ferramentas fundamentais em testes de intrusão, além de conceitos vitais para a segurança defensiva e ofensiva. Ao final, a teoria foi aplicada em laboratórios controlados com foco estritamente educacional.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

| Categoria | Ferramentas / Tecnologias |
| :--- | :--- |
| **Sistemas Operacionais** | Kali Linux, Windows 7, Windows XP, Windows 11, Linux |
| **Virtualização** | Oracle VM VirtualBox, VBoxManage |
| **Segurança da Informação** | Metasploit Framework, Metasploitable, Meterpreter, msfconsole, msfvenom, DVWA, Ettercap, Wireshark, Nmap |
| **Linguagens e Bibliotecas** | Python, HTML, Markdown, `os`, `pyaes`, `venv` |
| **Desenvolvimento & Versão** | Visual Studio Code, Nano, Git, GitHub |
| **Redes e Administração** | `ip`, `ifconfig`, `ipconfig`, Task Manager, UAC |

---

## 📖 Desenvolvimento das Atividades

### 4.1 🚀 Técnicas de Exploração de Vulnerabilidades
*   **Serviços Analisados:** FTP (autenticação anônima e falhas de config), RDP (exposição em Windows XP) e SSH (chaves, senhas fortes e controles de acesso).
*   **Metasploit Framework:** Estudo prático com `msfconsole`, `msfvenom` e gerenciamento de módulos e payloads.
*   **Meterpreter:** Interação remota para avaliação de privilégios.
*   **Backdoors:** Compreensão de acessos persistentes não autorizados e formas de mitigação.
*   *Prática:* Laboratórios com Kali Linux, Metasploitable, Windows XP e Windows 7 para simulação de conexões reversas e exploração de serviços vulneráveis.

### 4.2 🕵️‍♂️ Pós-Exploração em Sistemas Comprometidos
*   **Conceitos:** Análise pós-invasão, identificação de processos/usuários, escalonamento de privilégios (ex: elevate to SYSTEM/Admin), extração de dados e persistência.
*   **Automação:** Criação e execução de scripts de configuração automatizada via arquivos `.rc` do Metasploit.
*   *Aprendizados:* Reforço sobre o *princípio do menor privilégio*, monitoramento rigoroso de sessões e auditoria de logs.

### 4.3 🌐 Man in the Middle: Ataques e Mitigações
*   **Conceitos:** ARP Poisoning, manipulação de tabelas ARP e técnicas de *sniffing* de rede.
*   **Ferramentas:** Wireshark (análise de pacotes HTTP GET/POST) e Ettercap (interceptação de tráfego local).
*   **Mitigação:** Adoção obrigatória de HTTPS com certificados válidos, criptografia fim-a-fim, proteção contra ARP Spoofing e segmentação de redes.

### 4.4 💻 Desafio: Entendendo um Ransomware na Prática com Python
Projeto educacional focado em entender a lógica por trás de um ransomware utilizando criptografia simétrica.
*   **Tecnologia:** Python 3 + Biblioteca `pyaes` (modo CTR).
*   **Estrutura do Projeto:**
    *   `encrypter.py`: Script para criptografar o arquivo de teste.
    *   `decrypter.py`: Script para recuperar o conteúdo original usando a chave correta.
    *   `teste.txt`: Arquivo alvo dos testes.
*   *Nota de Segurança:* Experimento realizado estritamente em ambiente isolado (virtualenv) com fins de conscientização sobre backups e proteção de dados.

### 4.5 📚 Materiais Complementares
*   Documentações oficiais (Python, Metasploit, Wireshark, Ettercap, DVWA).
*   Repositórios de apoio e artigos técnicos voltados à segurança ofensiva e defensiva.

### 4.6 🎓 Conclusão
O módulo consolidou bases sólidas em **Vulnerability Assessment**, **Penetration Testing**, **Network Security** e **Incident Response**, destacando a importância vital de atualizações de sistemas, monitoramento contínuo e boas práticas de engenharia defensiva.

---

## 📂 Estrutura do Repositório

```text
boot_036/
│
├── README.md
├── meterpreter.rc
└── dp_ransomware/
    ├── encrypter.py
    ├── decrypter.py
    └── teste.txt
