# PROJETO-CYBERSEC-DIO - Leonardo Vieira
DOCUMENTAÇÃO - PROJETO PRÁTICO DE CIBERSEGURANÇA - DIO.

O projeto aqui documentado visa aplicar na prática os conhecimentos adquiridos durante o curso sobre ataques de força bruta em um ambiente controlado, usando máquinas virtuais com sistemas operacionais Kali Linux e Metasploitable 2. 
Os ataques foram feitos aos serviços FTP, DVWA e protocolo SMB. Ataques realizados usando os softwares Nmap, Medusa e Enum4Linux, para enumeração de serviços vulneráveis e tentativas de usuários e senhas de um arquivo wordlist. 

Para melhor experiência de visualização e entendimento a documentação do projeto foi criada em um arquivo PDF salvo neste repositório.
No documento é explicado de forma detalhada como foram realizados de forma prática cada um dos tópicos a seguir.

1 - Configuração do laboratório de testes
Criação das máquinas virtuais no Oracle VirtualBox, ambas as máquinas na mesma rede lógica para haver conexão.

2 - Iniciando o ataque usando Nmap + Medusa
O Software Nmap foi usado para enumeração das portas e o Medusa para o ataque de força bruta testando credenciais.

3 - Atacando formulário web (DVWA)
Ataque de força bruta para obter credenciais de acesso a um sistema web com login vulnerável.

4 - Ataque a usuários do protocolo SMB com Enum4Linux e Medusa - Técnica de password spraying.
O software Enum4Linux foi usado para enumerar usuários no alvo. O Medusa foi usado para realizar o password spraying.

5 -PREVENÇÃO / MITIGAÇÃO / RESPOSTAS AOS ATAQUES REALIZADOS


Conclusão

Este projeto demonstrou como ataques de enumeração e força-bruta (FTP, web login e SMB) podem ser executados com ferramentas como Nmap, Medusa e Enum4linux.
Foram identificadas e exploradas fragilidades típicas (senhas fracas, serviços expostos). A prática e a pesquisa realizada para o projeto contribuíram para
aumentar os conhecimentos em cyber-segurança, tanto na parte de ataque/auditoria e principalmente no sentido de saber como proteger os serviços da melhor forma possível. 
