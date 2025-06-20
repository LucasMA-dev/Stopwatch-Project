# ⏱️ Stopwatch Console App em C#

Um aplicativo de console simples de cronômetro desenvolvido em C#, parte do meu aprendizado no ecossistema .NET. Este projeto simula um cronômetro regressivo com contagem de segundos ou minutos, com uma interface minimalista no terminal.

---

## ✨ Funcionalidades

* **Contagem Regressiva Personalizável:** Defina o tempo em segundos (`s`) ou minutos (`m`).
    * Exemplo: `10s` para 10 segundos, `1m` para 1 minuto.
* **Contagem Visível:** Exibe o tempo atual no terminal, atualizando a cada segundo.
* **Mensagens Intuitivas:** Feedback visual como "Ready...", "Set...", "Go..." antes de iniciar a contagem.
* **Opção de Saída:** Encerre o aplicativo a qualquer momento digitando `0`.

---

## 🚀 Como Usar

Para executar este projeto na sua máquina:

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/LucasMA-dev/Stopwatch-Project.git](https://github.com/LucasMA-dev/Stopwatch-Project.git)
    ```
2.  **Navegue até a Pasta do Projeto:**
    ```bash
    cd Stopwatch-Project
    ```
3.  **Execute o Aplicativo:**
    ```bash
    dotnet run
    ```

    Após executar, o programa solicitará o tempo desejado no formato `[número][s/m]`.

    **Exemplos de entrada:**
    * `30s` (para 30 segundos)
    * `2m` (para 2 minutos)
    * `0` (para sair do aplicativo)

---

## 🛠️ Tecnologias Utilizadas

* **C#:** Linguagem de programação.
* **.NET:** Framework de desenvolvimento (utilizando `.NET Core` ou `.NET 5+`).

---

## 💡 Próximos Passos (Possíveis Evoluções)

* Adicionar funcionalidade de **pausar** e **retomar** o cronômetro.
* Implementar opções para **reiniciar** a contagem.
* Adicionar tratamento de erros mais robusto para entradas inválidas do usuário.
* Aprimorar a interface do usuário no console.

---

## 🤝 Contribuições

Sinta-se à vontade para abrir issues ou Pull Requests para sugerir melhorias, correções de bugs ou novas funcionalidades. Toda contribuição é bem-vinda!

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**Desenvolvido com 💙 por LucasMA-dev**