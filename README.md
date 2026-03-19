# 🚀 Codespace para C com Esteroides

<div align="center">
  <img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="150" alt="Terminal Matrix GIF">
  <br>
  <strong>Ambiente de desenvolvimento na nuvem pré-configurado para C e outras linguagens</strong>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/GitHub_Codespaces-181717?style=for-the-badge&logo=github&logoColor=white" alt="Codespaces">
</div>

---

## 🌟 Sobre o Template

Este repositório fornece um **ambiente de desenvolvimento pré-configurado** (Codespaces) focado em **C**, mas supertunado para diversas outras demandas. Ele inclui todos os softwares, extensões e ferramentas necessários para você começar a programar em segundos, direto no seu navegador, sem a necessidade de instalar absolutamente *nada* no seu computador local.

Criado originalmente como um *template* para as disciplinas de Programação do **Professor Ed** no Centro Universitário Unipê (João Pessoa - Paraíba).

### 📚 Linguagens Disponíveis
Além do ambiente robusto para C/C++, o container também oferece suporte nativo embutido para:
- **C / C++**
- **Python**
- **Rust**
- **HTML / CSS / Javascript**
- **Node.js**

### 🛠️ Features Instaladas no Container
O ambiente conta com esteroides reais! Algumas das *features* já ativadas por padrão:
- Ferramentas gerais: `docker-in-docker`, `sshd`, `pandoc`, `vscode-cli`, `vscode-server`, `shell-history`, `prettier`, `wasm32`, `cypress`, `cowsay`.
- Ecossistema Python completo: `pylint`, `pytest`, `python-launcher`, `pyupgrade`, `pyscaffold`, `pyoxidizer`.

---

## 💻 Instruções de Uso no Terminal

O ambiente já vem configurado para compilar e rodar seus códigos perfeitamente pelo terminal integrado. 

### Para compilar:
Você pode usar o utilitário `make` (a forma mais fácil):
```bash
make <nome_do_arquivo>
```
Ou compilar manualmente direto com o `gcc`:
```bash
gcc <nome_do_arquivo>.c -o <nome_do_arquivo>
```

> ⚠️ **Aviso sobre bibliotecas matemáticas:** Se no seu código C você incluir a biblioteca `<math.h>`, lembre-se de adicionar a *flag* `-lm` obrigatoriamente no final do comando de compilação se for usar o gcc manualmente:
> `gcc <nome_do_arquivo>.c -o <nome_do_arquivo> -lm`

### Para executar o programa:
Após a compilação ocorrer sem erros, execute o binário gerado digitando:
```bash
./<nome_do_arquivo>
```

---

## 👨‍💻 Autor

👋 Feito por **Prof. Ed (Edkallenn Lima)**
- ⭐️ Página Pessoal: [edkallenn.github.io](https://edkallenn.github.io/)
- 📧 E-mail: [edkallenn@yahoo.com.br](mailto:edkallenn@yahoo.com.br)
- 🌐 [LinkedIn](https://www.linkedin.com/in/edkallenn/) | [GitHub](https://github.com/ed1rac)
