# WaiterProject

# 📱 **Waiter Mobile**

O **Waiter Mobile** é a versão para dispositivos Android do sistema **Waiter**, um aplicativo de **gestão de restaurantes** que conecta clientes e funcionários em tempo real.
Inspirado nos sistemas de cardápios online via **QR Code**, o app permite ao cliente visualizar o menu, realizar pedidos e acompanhar o status em tempo real, enquanto o restaurante gerencia os pedidos de forma organizada e eficiente.

---

## 🧩 **Tecnologias Utilizadas**

* **Android Studio**
* **Java** (linguagem principal)
* **XML** (layout de interface)
* **MySql — para autenticação e armazenamento de dados
* **API REST (futuro)** — integração com a versão Web do sistema

---

## 📲 **Principais Funcionalidades**

| Código | Funcionalidade      | Descrição                                                          |
| :----: | ------------------- | ------------------------------------------------------------------ |
|   RF1  | Escanear QR Code    | O cliente acessa o cardápio digital ao escanear o QR Code da mesa. |
|   RF2  | Pesquisar           | Permite buscar pratos, bebidas e aperitivos.                       |
|   RF3  | Selecionar Item     | Adiciona itens ao carrinho de pedidos.                             |
|   RF4  | Realizar Pedido     | Envia o pedido diretamente ao sistema do restaurante.              |
|   RF5  | Avaliar Atendimento | O cliente pode avaliar sua experiência após o pedido.              |

## 🛠️ **Instalação e Execução**

### ✅ **Pré-requisitos**

* Android Studio Meerkat | 2024.3.1 Patch 1
Build #AI-243.24978.46.2431.13208083, built on March 13, 2025
Runtime version: 21.0.5+-13047016-b750.29 amd64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
Toolkit: sun.awt.windows.WToolkit
Windows 11.0
GC: G1 Young Generation, G1 Concurrent GC, G1 Old Generation
Memory: 2048M
Cores: 24
Registry:
  ide.experimental.ui=true

* Java JDK 21 javac 21.0.8


### ⚙️ **Como rodar o projeto**

1. Clone ou realize o download dos aqruivos no repositório com o link abaixo:

   ```
   https://github.com/devleopernardo/WaiterProject
   ```
2. Abra o projeto no Android Studio.
3. Aguarde o carregamento das dependências (Gradle).
4. Clique em **Run ▶️** para iniciar o app no emulador ou celular.

---

## 🧪 **Testes**

* Verifique se o QR Code abre o cardápio corretamente.
* Teste o fluxo de pedido completo (seleção → carrinho → envio).
* Avalie o layout em diferentes tamanhos de tela (celulares e tablets).

---

## 🧱 **Estrutura do Projeto**

```
waiter-mobile/
│
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/waiter/app/
│   │   │   │   ├── activities/
│   │   │   │   ├── adapters/
│   │   │   │   ├── models/
│   │   │   │   ├── services/
│   │   │   └── res/
│   │   │       ├── layout/
│   │   │       ├── values/
│   │   │       └── drawable/
│   ├── build.gradle
│
├── README.md
└── LICENSE
```

---

## 🚀 **Futuras Implementações**

* Integração com banco de dados (Firebase ou MySQL via API).
* Sistema de login para clientes e administradores.
* Painel de acompanhamento de pedidos.
* Histórico de avaliações.


