# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```

        🧑‍💻 1. Acesso root: sudo su
        Esse comando é usado para elevar privilégios no sistema Linux.

        sudo permite executar comandos como superusuário (root).

        su muda o usuário atual para o root.

        Resultado: você passa a ter controle total sobre o sistema — essencial para executar ferramentas como o SET.


- Iniciando o setoolkit: ``` setoolkit ```

        🚀 2. Iniciando o SET: setoolkit
        Esse comando inicia o Social-Engineer Toolkit, uma ferramenta interativa para simular ataques de engenharia social.

        Após rodar, ele abre um menu com várias opções de ataque.

        É usado por profissionais de segurança para testar vulnerabilidades humanas em sistemas.


- Tipo de ataque: ``` Social-Engineering Attacks ```

        🎯 3. Tipo de ataque: Social-Engineering Attacks
        Essa opção no menu do SET permite escolher ataques que exploram comportamento humano.

        Exemplos incluem phishing, spear phishing, e ataques por USB.

        Foco: enganar o usuário para obter acesso ou informações.

- Vetor de ataque: ``` Web Site Attack Vectors ```

        🌐 4. Vetor de ataque: Web Site Attack Vectors
        Essa categoria foca em ataques via navegador.

        Você pode clonar sites legítimos e capturar credenciais quando a vítima interage com eles.

        Muito usado em simulações de phishing.

- Método de ataque: ```Credential Harvester Attack Method ```

        🔐 5. Método de ataque: Credential Harvester Attack Method
        Essa técnica coleta credenciais digitadas pela vítima.

        Quando a vítima acessa o site falso e insere login/senha, o SET armazena essas informações.

        É uma das formas mais comuns de roubo de dados em testes de segurança


- Método de ataque: ``` Site Cloner ```

        🧬 6. Método de ataque: Site Cloner
        Essa função clona um site real (como Facebook, Gmail, etc.).

        O clone é hospedado localmente ou remotamente.

        A vítima acessa o clone achando que é o site verdadeiro — e insere suas credenciais.       


- Obtendo o endereço da máquina: ``` ifconfig ```

        📡 7. Obtendo o endereço da máquina: ifconfig
        Comando usado para ver os endereços IP da máquina.

        Essencial para saber qual IP usar ao hospedar o site falso.

        Exemplo: se você clonar um site, precisa informar o IP da sua máquina para que a vítima acesse.


- URL para clone:facebook

### Resutados

![Alt text](./passwd.png "Optional title")

# cibersecurity-desafio-phishing-master
Acesso root com sudo su para permissões administrativas.
Início do SEToolkit com setoolkit.
Escolha do ataque de engenharia social via site falso.
Clonagem de site com Site Cloner para capturar credenciais.
IP obtido com ifconfig para configurar o servidor de ataque.
