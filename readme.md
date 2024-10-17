## 🌍 **Conversor de Moedas**

Seja bem-vindo(a) ao projeto **Conversor de Moedas**, uma aplicação em Java que utiliza a API **ExchangeRate-API** para realizar conversões entre moedas de forma prática e rápida para o curso Backend da Alura!

---

### 📋 **Descrição**

O **Conversor de Moedas** é um projeto simples, porém poderoso, desenvolvido para mostrar como consumir APIs REST em Java utilizando a classe **HttpClient** e explorar recursos modernos da linguagem, como o tipo `var`. Ideal para quem quer aprender sobre APIs, JSON, e boas práticas de manipulação de dados no Java.

---

### 🛠️ **Tecnologias Utilizadas**

- **Java 11+**: Linguagem principal
- **Gradle**: Para automação de build
- **Jackson**: Para processar JSON
- **ExchangeRate-API**: API de conversão de moedas
- **HttpClient**: Cliente HTTP nativo do Java

---

### 🚀 **Como Executar o Projeto**

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/seu-usuario/conversor-de-moedas.git
   cd conversor-de-moedas
   ```

2. **Adicione a dependência Jackson** no `build.gradle`:

   ```groovy
   dependencies {
       implementation 'com.fasterxml.jackson.core:jackson-databind:2.15.2'
   }
   ```

3. **Compile e execute o projeto**:

   ```bash
   ./gradlew run
   ```

4. **Siga as instruções no terminal**:
   - Digite o código da moeda de origem (ex: USD)
   - Informe a quantidade (ex: 100)
   - Digite o código da moeda de destino (ex: BRL)

---

### 💡 **Exemplo de Uso**

```bash
Insira o código de uma moeda:
USD
Insira a quantidade:
100
Insira o código de outra moeda para conversão:
BRL
Resultado da conversão: 520.35
```

### 📄 **Licença**

Este projeto é licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais informações.

---

**Divirta-se explorando o mundo das conversões!** 🌐💰
