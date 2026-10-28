<div align="center">

# Olá, eu sou o Matheus Putrique! 👋

**Estudante de Engenharia de Software & Análise e Desenvolvimento de Sistemas (ADS) | Desenvolvedor Back-End & Mobile**  
*Focado em Programação Orientada a Objetos (POO) com Java e arquitetura de sistemas*

[![GitHub](https://img.shields.io/badge/GitHub-Matheus--Putrique-181717?style=for-the-badge&logo=github)](https://github.com/Matheus-Putrique)
[![Gmail](https://img.shields.io/badge/Email-matheusputrique%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matheusputrique@gmail.com)

</div>

---

### 👨‍💻 Sobre Mim

Sou estudante de **Engenharia de Software** e de **Análise e Desenvolvimento de Sistemas (ADS)**, apaixonado por transformar regras de negócio reais em código limpo, modular e bem estruturado. 

Meu foco principal está no ecossistema **Java** e nos pilares da **Programação Orientada a Objetos (POO)** — aplicando **Encapsulamento, Herança, Polimorfismo, Abstração, Interfaces, Composição e Enums** na construção de sistemas robustos. Também desenvolvo aplicações mobile nativas para Android utilizando **Kotlin** e **Jetpack Compose**, além de explorar **C#**, **PHP** e bancos de dados relacionais (**MySQL**).

---

### ☕ Foco em Engenharia de Software & POO (Java)

Acredito que uma base sólida em Orientação a Objetos é o que diferencia um código simples de um sistema escalável. Nos meus projetos em Java, busco aplicar:

- **Polimorfismo & Contratos com Interfaces:** Uso de interfaces (Strategy/Polimorfismo) para desacoplar regras de negócio complexas que variam conforme o contexto.
- **Composição & Relacionamento entre Objetos:** Modelagem de domínios ricos onde entidades interagem diretamente entre si (associações 1:N e N:N), evitando dados soltos.
- **Enums Ricos & Máquinas de Estado:** Controle estrito de fluxo e estados de entidades (`StatusSocio`, `StatusOS`, `Cargo`, `RegiaoEstadio`) com atributos e comportamentos encapsulados.
- **Arquitetura em Camadas & MVC:** Separação clara entre modelos de domínio (`model`), regras de negócio (`service`) e controle/interação (`controller` / `view`).
- **Tratamento de Exceções & API de Datas (`java.time`):** Validações defensivas (`IllegalStateException`, `IllegalArgumentException`) e manipulação precisa de janelas de tempo com `LocalDate` e `LocalDateTime`.

---

### 🚀 Principais Sistemas & Projetos em Destaque

#### 🏟️ [Sistema de Gestão de Sócio-Torcedor (`Sistema-SocioTorcedor`)](https://github.com/Matheus-Putrique/Sistema-SocioTorcedor)
Sistema em Java (Maven) que simula o gerenciamento completo de um programa de sócio-torcedor e controle de acesso a estádio.
- **Destaques de POO:** Implementação da interface `ModalidadeSocio` com polimorfismo entre múltiplos planos (`PlanoMuralha`, `PlanoTradicao`, `PlanoImperial`, `PlanoPresidencial`).
- **Regras de Negócio:** Serviço de check-in (`ServicoCheckin`) com validação de status do sócio, permissão de acesso por setor do estádio (`RegiaoEstadio`), controle de capacidade máxima por setor, prevenção de check-in duplicado e cálculo dinâmico de janelas de abertura/fechamento com `LocalDateTime`.

#### 🍔 [Sistema PDV & Controle de Estoque (`pos-inventory-system-java`)](https://github.com/Matheus-Putrique/pos-inventory-system-java)
Aplicação de Ponto de Venda (PDV), autoatendimento e gestão de estoque orientada a objetos escrita em Java.
- **Destaques de POO:** Composição entre `Pedido`, `ItemPedido` e `Produto`, garantindo baixa automática e validada de estoque no momento da adição ao pedido.
- **Controle de Acesso por Cargo:** Autenticação de colaboradores (`Funcionario`) com roteamento dinâmico de menus e permissões baseado em `Cargo` (`CHEFE`, `GERENTE`, `ATENDENTE`, `COZINHEIRO`), separando o painel gerencial (CRUD de produtos e reposição de estoque) do painel operacional (fila e despacho de pedidos).

#### 🛠️ [Gestor de Ordens de Serviço (`Gestor_De_Servi-o`)](https://github.com/Matheus-Putrique/Gestor_De_Servi-o)
Sistema para controle de fluxo de ordens de serviço (OS) em uma oficina mecânica.
- **Destaques de POO:** Modelagem de `OrdemServico` composta por múltiplos `ItemServico`, controle de ciclo de vida via enum (`StatusOS`: `PENDENTE`, `EM_ANDAMENTO`, `CONCLUIDO`, `CANCELADA`), bloqueio de alterações em ordens finalizadas e registro temporal com `LocalDate` e `LocalDateTime`.

#### 📚 [Sistema de Gerenciamento de Biblioteca (`Sistema-de-biblioteca-simples-JAVA`)](https://github.com/Matheus-Putrique/Sistema-de-biblioteca-simples-JAVA)
Sistema para catalogação e gerenciamento de acervo bibliográfico focado em associação de objetos.
- **Destaques de POO:** Substituição de tipos primitivos/Strings soltas por relacionamentos reais entre objetos (`Biblioteca`, `Livro`, `Autor`, `Editora` e `Categoria`), permitindo buscas cruzadas e alta coesão dos dados.

#### 📱 [Forge Burger App (`forge_burger_app-2.0`)](https://github.com/Matheus-Putrique/forge_burger_app-2.0)
Aplicativo Android nativo desenvolvido em **Kotlin** e **Jetpack Compose** para cardápio digital, personalização de pedidos e gerenciamento de carrinho de uma hamburgueria artesanal.

---

### 🛠️ Tecnologias e Ferramentas

<div align="center">

| Categoria | Tecnologias |
| :--- | :--- |
| **Linguagem Principal & POO** | ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white) |
| **Desenvolvimento Mobile** | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white) |
| **Outras Linguagens & Web** | ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white) |
| **Banco de Dados & Ferramentas** | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) |

</div>

---

### 📊 Estatísticas do GitHub

<div align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=Matheus-Putrique&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Matheus-Putrique&layout=compact&langs_count=6&theme=tokyonight&hide=python&hide_border=true"/>
</div>
