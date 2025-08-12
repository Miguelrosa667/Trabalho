### 🌐 **Selenium**

**Selenium** é uma biblioteca amplamente utilizada para **automação de navegadores web**. Muito popular em testes automatizados de aplicações web, também é utilizada para **web scraping** e preenchimento automático de formulários. É uma ferramenta **multiplataforma e multilíngue**, com suporte para linguagens como Python, Java, C#, Ruby, Perl e JavaScript.

#### ✅ Principais funcionalidades:

- Abrir e controlar navegadores como Chrome, Firefox, Edge e Safari.
- Preencher campos de texto, clicar em botões e navegar por páginas.
- Capturar e interagir com elementos HTML dinâmicos.
- Execução de testes automatizados de forma robusta e escalável.

#### 👍 Pontos Positivos:

- Suporte a múltiplos navegadores e linguagens de programação.
- Útil tanto para automação de tarefas como para testes automatizados.
- Pode simular interações humanas reais com a página.
- Comunidade ativa e boa documentação.

#### 👎 Pontos Negativos:

- Requer configuração de **drivers** específicos para cada navegador.
- Mais lento que outras formas de web scraping (como `requests + BeautifulSoup`).
- Pode ser instável com páginas muito dinâmicas (JS pesado).
- Não é ideal para aplicações sem interface gráfica (headless requer setup extra).

---

### 🖱️ **PyAutoGUI**

**PyAutoGUI** é uma biblioteca focada na **automação da interface gráfica do usuário (GUI)**. Permite controlar o **mouse**, **teclado**, **capturar imagens da tela** e interagir com janelas do sistema operacional. É muito usada para automações de tarefas manuais ou repetitivas em softwares que não têm API.

#### ✅ Principais funcionalidades:

- Mover e clicar o mouse em coordenadas específicas.
- Digitar textos automaticamente como se fosse o usuário.
- Capturar imagens da tela e localizar elementos visuais.
- Suporte a automações multiplataforma (Windows, macOS, Linux).

#### 👍 Pontos Positivos:

- Extremamente simples de usar e configurar.
- Funciona em qualquer aplicativo visível na tela.
- Ideal para tarefas repetitivas em softwares sem API ou integração.
- Permite automações visuais baseadas em reconhecimento de imagem.

#### 👎 Pontos Negativos:

- Não funciona bem com interfaces minimizadas ou que mudam de posição/resolução.
- Menos preciso em ambientes com múltiplas telas ou DPI elevado.
- Não reconhece o conteúdo da janela, apenas a imagem (sem acesso ao DOM).
- Pode falhar se a interface mudar ligeiramente (cor, posição, tamanho).

---
