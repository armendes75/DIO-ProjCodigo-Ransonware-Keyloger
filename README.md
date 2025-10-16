# DIO - Desafio de Código - Santander - Cibersegurança 2025
## Simulação de Código para Ransonware e KeyLogger

## Descrição 

Abaixo vamos mostrar e explicar os dois códigos em Python para simulação de Ransonware e Keylogger
conforme determinação da tarefa do projeto e em seguida vamos dar as dicas de proteção.
Obs. os códigos abaixos são para efeito de estudo e simulação.

#### 1. Ransonware
#### 2. Keyloogger
#### 3. Como se proteger

## 1. Ransonware

Ransonware é um tipo de Malware muito utilizado hoje em dia pelos criminosos virtuais para criptografar os dados, sequestrar os dados e pedir resgate pelos menos, ou seja ganhar dinheiro com o sequestro virtual de dados.
Vamos ver a seguir como o ransonware funciona, um exemplo de código e dicas de proteção.

### Como o Ransonware funciona

- Ele primeiro faz toda uma extracificação de dados, ou seja, o criminoso copia/rouba todos os dados da vítima.
- Em seguida, ele criptografa todos os dados, ou seja, ele trava, inutiliza os dados a ponto qu eo usuário não consegue mais utilizá=lo
- Deixa uma mensagem pedindo dinheiro em formato de bitcoins / criptomoeda para não ser rastreável para poder liberar os dados novamente para a vitima.
- Se o usuário pagar o resgate solicitado pelo crimonioso,pode ser que ele receba o chave para descritografar os adados e poder ter seus dados novamente, ou não, ou seja, não significa que s epagar vc terá seus dados de volta, estamos lidando com criminosos.

### Exemplo de Código

Na pasta código, tem o arquivo ransonware.txt com o código. Não é um malware de verdade, só server para efeito de teste e aprendizado, mas mesmo assim deve ser usado com cuidado e para fins éticos.

### Como se proteger

- Antivírus ataualizado e moderno
- Firewall
- Softwares para deteção de comportamento
- Cuidado ao abrir arquivos e links
- ter sempre backups

## 2. Keylogger

Keylogger é um tipo de malware que captura tudo o qu eo usuário está fazendo ou vendo em seu computador. ele pode capturar todas as teclas digitadas, telas e muito mais, e enviar isso para o criminoso virtual.
É assim que geralmente os criminosos roubam os usuários e senhas das vítimas.

### Como o Keylogger funciona

- é um programa que é instalado no micro da vítima e fica funcionando de forma oculta, em a vítima perceber
- ele pode ser instalado atraves de um arquivo ou link que a vítima utilizou, e muitas vezes não são detectáveis pelos antivírus, principalmente os mais simples
- Captura tudo o que o usuários digita ou faz e envia para o criminoso

### Exemplo de código

No arquivo Keylogger.txt na pasta codigos tem um expmplo de keylogger para uso de estudo e teste, não deve ser usado para outra finalidade.

### Com se proteger:
- Cuidado com o que acessa
- antivírus atualizado

## 3. Como Se proteger de Ransonware e Keylogger

🧩 Atualizações e patches

Mantenha sistema operacional, navegadores e softwares atualizados.

Habilite atualizações automáticas.

Use versões recentes de bibliotecas e frameworks em servidores.

🧱 Antivírus e EDR

Utilize uma solução de segurança confiável (Windows Defender, Kaspersky, BitDefender, CrowdStrike, etc.).

Ative proteção em tempo real e escaneamento periódico.

Monitore alertas de comportamento suspeito (modificações em massa de arquivos, processos estranhos).

🌐 Firewall e controle de rede

Bloqueie conexões externas desnecessárias (saídas de portas não utilizadas).

Monitore tráfego de rede — ransomwares muitas vezes tentam comunicar-se com servidores C2 (Command & Control).

🧑‍💻 Privilégios mínimos

Nunca use conta de administrador para tarefas diárias.

Restrinja acesso a pastas críticas.

Use User Account Control (UAC) e autenticação multifator (MFA) sempre que possível.

🔐 Backups

Faça cópias regulares de arquivos importantes.

Guarde uma cópia offline (HD externo desconectado ou backup em nuvem com controle de versão).

Teste seus backups (verifique se consegue restaurar).

🕵️ Monitoramento e logs

Ative logs de sistema e mantenha ferramentas de auditoria (Sysmon, Splunk, ELK).

Use monitoramento de integridade de arquivos (File Integrity Monitoring).

🚫 Cuidado com phishing

Desconfie de e-mails urgentes ou que pedem cliques/instalações.

Passe o mouse sobre links para ver o destino real.

Nunca baixe anexos de remetentes desconhecidos.

🧾 Downloads e software

Baixe apenas de fontes oficiais.

Evite “cracks”, “ativadores” ou programas pirateados (frequentemente carregam trojans e keyloggers).

🌍 Navegação segura

Use navegadores atualizados e extensões de privacidade (uBlock Origin, HTTPS Everywhere).

Evite sites de procedência duvidosa.

🔑 Senhas e autenticação

Use senhas fortes e únicas.

Utilize gerenciador de senhas (Bitwarden, 1Password, KeePassXC).

Ative MFA (autenticação em dois fatores) sempre que possível.

