# instalacao_netBeans
manual de instalação
Para instalar o JDK e a IDE NetBeans em um sistema Linux, siga os passos abaixo:

### Passo 1: Instalação do JDK

1. **Abra o terminal**.
2. **Atualize o sistema**:
   ```bash
   sudo apt update
   sudo apt upgrade
   ```
3. **Instale o JDK** (substitua `openjdk-11-jdk` pela versão desejada, se necessário):
   ```bash
   sudo apt install openjdk-11-jdk
   ```
4. **Verifique a instalação do JDK**:
   ```bash
   java -version
   ```

### Passo 2: Instalação do NetBeans

1. **Baixe o instalador do NetBeans**:
   Acesse o site oficial do NetBeans e baixe a versão desejada. Você pode usar o comando `wget` para baixar diretamente no terminal. Por exemplo:
   ```bash
   wget https://downloads.apache.org/netbeans/22/Apache-NetBeans-22-bin-linux-x64.sh
   ```
   (Certifique-se de que o link está correto e atualizado).

2. **Dê permissão de execução ao instalador**:
   ```bash
   chmod +x Apache-NetBeans-22-bin-linux-x64.sh
   ```

3. **Execute o instalador**:
   ```bash
   ./Apache-NetBeans-22-bin-linux-x64.sh
   ```

4. **Siga as instruções do instalador**:
   - Aceite os termos de uso.
   - Escolha o local de instalação (recomenda-se manter o padrão).
   - Complete a instalação.

### Passo 3: Iniciar o NetBeans

1. **Após a instalação, você pode iniciar o NetBeans**:
   - Você pode encontrá-lo no menu de aplicativos ou iniciar pelo terminal com:
   ```bash
   netbeans
   ```

### Observações

- Caso encontre problemas de compatibilidade entre o JDK e o NetBeans, considere instalar uma versão mais antiga do JDK.
- Para desinstalar o JDK ou o NetBeans, você pode usar os comandos:
  ```bash
  sudo apt remove openjdk-11-jdk
  ```
  e, para o NetBeans, siga as instruções específicas de desinstalação do instalador que você usou.

Esses passos devem ajudá-lo a instalar o JDK e o NetBeans em um sistema Linux com sucesso!
