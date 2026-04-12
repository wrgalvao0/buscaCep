# 🔍 Busca CEP

Uma aplicação web simples e intuitiva para consultar endereços brasileiros através do CEP (Código de Endereçamento Postal).

## Descrição

**Busca CEP** é uma ferramenta web que permite aos usuários localizar endereços completos digitando apenas o CEP. A aplicação utiliza a API pública [ViaCEP](https://viacep.com.br/) para buscar informações precisas e atualizadas sobre logradouros, bairros, cidades e estados do Brasil.

## Objetivo

Fornecer uma forma rápida, fácil e acessível para consultar endereços brasileiros, útil para:
- Preenchimento de formulários de cadastro
- Verificação de endereços
- Pesquisa de localização geográfica
- Validação de CEPs

## 🚀 Funcionalidades

- ✅ Busca de endereço por CEP
- ✅ Validação de formato de CEP (8 dígitos)
- ✅ Exibição de informações completas:
  - Logradouro
  - Bairro
  - Complemento
  - Cidade
  - Estado (UF)
- ✅ Botão para limpar dados e nova consulta
- ✅ Interface responsiva e amigável
- ✅ Design moderno com Bootstrap

## 📱 Acesso Online

A aplicação está disponível no GitHub Pages e pode ser acessada gratuitamente através do link:

🔗 **[https://wrgalvao0.github.io/buscaCep/](https://wrgalvao0.github.io/buscaCep/)**

Basta abrir o link no seu navegador e começar a consultar CEPs!

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura
- **CSS3** - Estilização
- **JavaScript (Vanilla)** - Lógica e interatividade
- **Bootstrap 5.3** - Framework CSS responsivo
- **Bootstrap Icons** - Biblioteca de ícones
- **ViaCEP API** - Integração de dados de CEP
- **Docker** - Containerização

## 💻 Como Usar Localmente

### Pré-requisitos
- Navegador web moderno
- (Opcional) Docker para executar em container

### Sem Docker
1. Clone o repositório:
```bash
git clone https://github.com/wrgalvao0/buscaCep.git
cd buscaCep
```

2. Abra o arquivo `index.html` no seu navegador

### Com Docker
1. Clone o repositório:
```bash
git clone https://github.com/wrgalvao0/buscaCep.git
cd buscaCep
```

2. Construa a imagem Docker:
```bash
docker build -t busca-cep .
```

3. Execute o container:
```bash
docker run -p 8080:80 busca-cep
```

4. Acesse em seu navegador: `http://localhost:8080`

## 📝 Como Funciona

1. Digite um CEP válido (8 dígitos) no campo de entrada
2. Clique no botão **"Consultar"**
3. A aplicação faz uma requisição à API ViaCEP
4. Os dados do endereço são exibidos abaixo do formulário
5. Use o botão **"Limpar"** para resetar e fazer uma nova consulta

## 📌 Exemplo de Uso

Para consultar um CEP famoso no Brasil, por exemplo `01310100` (Avenida Paulista em São Paulo):
- **Logradouro**: Av Paulista
- **Bairro**: Bela Vista
- **Complemento**: lado ímpar
- **Cidade**: São Paulo
- **Estado**: SP

## 🔗 Repositório GitHub

[https://github.com/wrgalvao0/buscaCep](https://github.com/wrgalvao0/buscaCep)

## 📄 Licença

Este projeto é de código aberto e pode ser utilizado livremente.

---

**Desenvolvido por [Wrgalvão](https://github.com/wrgalvao0)**
