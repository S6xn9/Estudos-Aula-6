
# 🧠 Anotações de Estudo: Hierarquia de Títulos em HTML
📅 Criado em: **18 de julho de 2025**  
📚 Matéria:**Programação Web (HTML5 e CSS3)**  
✍️ Autor: **Marco**

## 📌 Assunto: Hierarquia de Títulos (HTML)

---

### 1. O que são títulos em HTML?

Títulos em HTML são elementos que ajudam a **organizar e estruturar o conteúdo** de uma página web. Além disso, eles têm uma importância gigante pra **acessibilidade**, **SEO** e até pra leitura humana mesmo.

#### ✅ Para que servem?
- **Organização do conteúdo**: Deixam tudo mais claro e dividido em partes lógicas.
- **SEO (Search Engine Optimization)**: Motores de busca como o Google entendem melhor o conteúdo da página com base nos títulos.
- **Acessibilidade**: Leitores de tela usam os títulos pra pular direto pras seções que interessam ao usuário.

---

### 2. Os elementos de título: `<h1>` até `<h6>`

O HTML oferece 6 níveis de título, do mais importante (`<h1>`) até o menos (`<h6>`). Cada nível serve pra indicar a **importância e estrutura** do conteúdo.

#### 🔹 `<h1>` – Título Principal
- É o **mais importante** da página.
- Deve ser **único** por página.
- Geralmente representa o **tema central**.
- **Exemplo:**  
  ```html
  <h1>Meu Blog de Receitas</h1>
  ```

#### 🔹 `<h2>` – Seções principais
- Usado pra dividir o conteúdo do `<h1>` em **blocos principais**.
- Pode ter **vários `<h2>`** numa mesma página.
- **Exemplo:**  
  ```html
  <h2>Receitas Doces</h2>
  <h2>Receitas Salgadas</h2>
  ```

#### 🔹 `<h3>` – Subdivisões do `<h2>`
- Subtítulos dentro de uma seção do `<h2>`.
- **Exemplo:**
  ```html
  <h3>Bolo de Chocolate</h3>
  ```

#### 🔹 `<h4>` – Subdivisões do `<h3>`
- Vai mais a fundo nos detalhes de uma subseção.
- **Exemplo:**
  ```html
  <h4>Ingredientes</h4>
  <h4>Modo de Preparo</h4>
  ```

#### 🔹 `<h5>` e `<h6>` – Detalhes bem específicos
- São pouco usados no dia a dia.
- Úteis em **documentos muito longos** ou com estrutura muito complexa.

---

### 3. Boas práticas da hierarquia de títulos

✔️ **Use em ordem lógica:**  
Nada de pular do `<h1>` pro `<h3>`. Sempre vá descendo de nível: `<h1> → <h2> → <h3>`, e assim por diante.

✔️ **Semântica acima do visual:**  
Escolha o título pelo **significado do conteúdo**, não pelo tamanho da letra. Quer título maior? Faz isso com CSS, não mudando de `<h2>` pra `<h1>` só pra ficar maior.

✔️ **Um `<h1>` por página (recomendado):**  
Mesmo que o HTML5 aceite vários `<h1>`, o ideal é usar **um só**, pra deixar tudo claro pro SEO e leitores de tela.

✔️ **Títulos claros e objetivos:**  
Evita enrolar. O título tem que dizer **exatamente** do que aquela parte está falando.

---

### 4. Por que isso é importante na prática?

- 🧩 **Organização da leitura**: Ajuda o visitante (ou você mesmo no futuro) a encontrar o que precisa rápido.
- 📈 **Melhora o SEO**: Títulos bem usados = site mais fácil de ser entendido pelos mecanismos de busca.
- ♿ **Acessibilidade real**: Leitores de tela transformam a hierarquia de títulos em uma espécie de "índice navegável".

---

### 🚀 Resumo do Resumo

A hierarquia de títulos não é só questão de estilo, é **estrutura**, **semântica** e **acessibilidade**. Se usada da forma certa, ajuda tanto os humanos quanto os robôs a entenderem melhor o conteúdo.
