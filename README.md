
<h1 align="center">
  <br>
  <a href=""><img src="./assets/logo-waiter.svg" alt="logo do waiter" width="250"></a>
  <br>
  <br>
</h1>

# 📱 **Waiter Mobile**

O **Waiter Mobile** é a versão para dispositivos Android do sistema **Waiter**, um aplicativo de **gestão de restaurantes** que conecta clientes e funcionários em tempo real.
Inspirado nos sistemas de cardápios online via **QR Code**, o app permite ao cliente visualizar o menu, realizar pedidos e acompanhar o status em tempo real, enquanto o restaurante gerencia os pedidos de forma organizada e eficiente.

---

## 🧩 **Tecnologias Utilizadas**

* **Android Studio**
* **Java** (linguagem principal)
* **XML** (layout de interface)
* **MySql — para autenticação e armazenamento de dados

---

## 📲 **Principais Funcionalidades**

| Código | Funcionalidade      | Descrição                                                          |
| :----: | ------------------- | ------------------------------------------------------------------ |
|   RF1  | Login                     | Login Correto com autenticacao.                                    | 
|   RF2  | Cadastrar                 | Ler, Cadastrar, Alterar, Excluir Usuarios.                         |
|   RF3  | Recuperar Senha           | Recuperar Senha, quando o usuario perde a senha.                   |
|   RF4  | Gestao Administrativa     | Manter usuario, Contabilizar Contar e Manter Cardapio.             |



## 🛠️ **Instalação e Execução**

### ✅ **Pré-requisitos**

* Android Studio Meerkat | 2024.3.1 Patch 1
ou Posterior

* Java JDK 21 javac 21.0.8

* MySql Workbench


### ⚙️ **Como rodar o projeto**

1. Realize o download dos aqruivos no repositório com o link abaixo:

   ```
https://mega.nz/file/yUkzkLAL#iNv6TtOpsN1Slh9EON3LAP0S-lKxNhd-C_e3-RtSa7w
   ```
2. Copie a pasta "WaiterBeta.zip" .
3. Cole e Extraia a pasta "gradlew" no diretorio Android Studio Project.
  segue um caminho exemplo: C:\Users\leonardo33566416\AndroidStudioProjects para encontrar o diretorio.
4. Abra o MySql Workbench
5. Abra um novo SQL file, cole a seguinte sequencia e execute :

CREATE USER 'senac'@'%' IDENTIFIED BY '123';

GRANT ALL ON *.*
TO 'senac'@'%';

6. Abra o Android Studio
5. Aguarde o carregamento das dependências (Gradle).
4. Clique em **Run ▶️** para iniciar o app no emulador ou celular.

---



