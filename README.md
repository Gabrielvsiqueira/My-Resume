# My Resume - Gabriel Vitor Siqueira

Este repositório contém o código-fonte do meu currículo, escrito em LaTeX. O processo de compilação e versionamento é totalmente automatizado usando GitHub Actions.

## ✨ Visão Geral

O objetivo deste projeto é manter um currículo profissional e atualizado de forma programática, garantindo o controle de versão e a geração automática de PDFs para distribuição.

A cada nova tag (`v1.0`, `v1.1`, etc.) enviada ao repositório, uma action é acionada para compilar as versões em Inglês e Português do currículo e publicá-las em uma nova **Release** no GitHub.

## 📄 Acessando o Currículo

Você pode visualizar e baixar a versão mais recente dos currículos diretamente pelos links abaixo:

- **[Currículo em Inglês (PDF)](https://github.com/Gabrielvsiqueira/My-Resume/releases/latest/download/curriculum.pdf)**
- **[Currículo em Português (PDF)](https://github.com/Gabrielvsiqueira/My-Resume/releases/latest/download/curriculum-pt.pdf)**

## 🚀 Como Gerar uma Nova Versão

Para gerar uma nova versão dos arquivos PDF, basta criar e enviar uma nova tag para o repositório. O fluxo de trabalho é o seguinte:

1.  Crie uma tag semântica (ex: `v1.2.0`):

    ```sh
    git tag -a v1.2.0 -m "feat: Atualiza experiência profissional"
    ```

2.  Envie a tag para o repositório remoto:
    ```sh
    git push origin v1.2.0
    ```

Após o push da tag, a GitHub Action será iniciada e, em poucos minutos, a nova release com os PDFs atualizados estará disponível.

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: LaTeX
- **Estilo**: `moderncv`
- **Automação**: Make
- **CI/CD**: GitHub Actions
- 
Este projeto foi inspirado no repositório [resume do @Calebe94](https://github.com/Calebe94/resume).
