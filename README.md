# Relatório RQM

Utilitário Java para geração de relatórios Excel e gerenciamento de recursos dentro do IBM Rational Quality Manager (RQM).

## Pré-requisitos

- Java 7 (JDK 1.7)
- Eclipse IDE (recomendado)
- Bibliotecas IBM RQM SDK (incluídas no classpath)

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/rafaelakio/relatoriorqm.git
```

2. Importe o projeto no Eclipse como "Existing Projects into Workspace"
3. Configure as bibliotecas IBM RQM no build path

## Como Usar

- Execute a classe principal para gerar relatórios Excel a partir do RQM
- Use o `CopyUtil` para duplicar recursos de teste no IBM RQM

## Arquitetura

- **`src/`**: Código-fonte Java para lógica de relatórios
- **`bin/`**: Diretório de saída para bytecode compilado
- Utiliza bibliotecas IBM RQM-Extras para integração com o Quality Manager

## Como Contribuir

Veja [CONTRIBUTING.md](CONTRIBUTING.md) para diretrizes de contribuição.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
