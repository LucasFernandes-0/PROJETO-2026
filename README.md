cibersegurança-desafio-phishing
Projeto da formação Cybersecurity Specialist da DIO, onde criamos uma página de login falsa para captura de senhas. Utiliza o sistema operacional Kali Linux e a ferramenta setoolkit.

Ao rodar o setoolkit, escolhemos Social Engineering Attacks e Website Attack Vectors. Depois, Credential Harvester Attack Method e Custom Import.
<img width="1457" height="993" alt="1" src="https://github.com/user-attachments/assets/c5942da1-8927-4f70-be5d-a4357201944a" />
<img width="1313" height="951" alt="2" src="https://github.com/user-attachments/assets/e02b953e-a512-4f62-aff0-e47c18bfa5a7" />
<img width="1445" height="862" alt="3" src="https://github.com/user-attachments/assets/5bd58c40-457c-42fa-a838-d799b73ab883" />



<img width="1532" height="890" alt="4" src="https://github.com/user-attachments/assets/1e2cb7fa-aa28-4265-88c5-011a0c3164e7" />
<img width="1420" height="779" alt="5" src="https://github.com/user-attachments/assets/cb393ff9-cb92-48fe-aed6-8e04bbb7dbde" />
Definimos o IP da máquina, apontamos o caminho até o diretório onde está localizado o formulário de login falso (index.html). O programa então serve a página na porta 80.
<img width="1490" height="702" alt="6" src="https://github.com/user-attachments/assets/3d0042ca-9d49-4332-b467-da44e453fc1a" />
Acessando pelo navegador, o console do setoolkit gera um aviso de requisição GET indicando que abrimos. Inserimos um usuário e senha e, ao clicar no botão, esses dados são automaticamente capturados e exibidos no console do setoolkit.

<img width="1871" height="747" alt="8" src="https://github.com/user-attachments/assets/20b97e31-42d2-4791-8364-fdc20b5e72f8" />

<img width="1156" height="594" alt="9" src="https://github.com/user-attachments/assets/af494f26-f8e6-4d16-a272-18a30c0bfb77" />


