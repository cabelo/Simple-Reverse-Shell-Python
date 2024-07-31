# Remote Shell

Este projeto implementa uma shell remota que se conecta a um servidor de controle, permitindo a execução de comandos de shell remotamente.

## Funcionalidades

- Conecta a um servidor de controle via socket.
- Recebe e executa comandos enviados pelo servidor.
- Envia a saída dos comandos de volta para o servidor.
- Permite a mudança de diretório remoto.
- Finaliza a conexão quando o comando "exit" é recebido.

## Como Usar

### Requisitos

- Python 3.x

### Configuração

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/remoteshell.git
    cd remoteshell
    ```

2. Atualize as configurações de IP e porta no código se necessário.

3. Execute o script:
    ```bash
    python remoteshell.py
    ```

## Segurança

⚠️ **Aviso**: Este script é para fins educacionais e de teste. Não use em ambientes de produção ou sistemas sem autorização explícita. Usar este script pode ser ilegal em muitos países se utilizado sem permissão.
