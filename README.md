# PodeVotar - Teste de Software com ASP.NET e xUnit

Este projeto foi desenvolvido como parte de uma atividade prática para testes de software, utilizando **ASP.NET** e **xUnit**. Durante o desenvolvimento, revisei e corrigi o código para validar corretamente as faixas etárias em que o voto é:

- **Obrigatório**: Para cidadãos de 18 a 70 anos.
- **Opcional**: Para cidadãos entre 16 e 17 anos, ou acima de 70 anos.
- **Não pode Votar**: Para cidadãos abaixo de 16 anos.

## Objetivo do Projeto

O principal foco foi identificar e corrigir bugs no código, implementar testes unitários e utilizar o framework **xUnit** para validação. O trabalho envolveu:

- Revisar o código existente, compreendendo as regras de votação.
- Identificar bugs nas funções de verificação de idade.
- Garantir que os testes cobrissem corretamente todos os cenários.
- Melhorar os testes e corrigir falhas onde necessário.

Os alunos devem revisar o código, entender as regras de votação e corrigir eventuais problemas nos testes e nas funções associadas à verificação de idade.

## Como Executar o Projeto

### Requisitos

- **ASP.NET Core** 5.0 ou superior
- **xUnit** para testes unitários

### Passos para Clonar e Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/PodeVotar.git
   ```
2. **Navegue até a pasta do projeto**:
   ```bash
   cd PodeVotar
   ```
3. **Abra o projeto no Visual Studio** ou outro IDE de sua preferência.
4. **Restaure as dependências**:
   No Visual Studio, clique com o botão direito no projeto e selecione "Restore NuGet Packages".
   
5. **Execute os testes**:
   Você pode executar os testes unitários diretamente do Visual Studio ou via terminal usando o seguinte comando:
   ```bash
   dotnet test
   ```

## Exemplo de Cenários de Teste

- **Voto obrigatório**: Cidadãos com idade entre 18 e 70 anos.
- **Voto opcional**: Cidadãos de 16-17 anos ou acima de 70 anos.
- **Não pode Votar**: Cidadãos com menos de 16 anos.

Com as correções e ajustes feitos, submeti o código final ao GitHub.

## Licença

Este projeto é distribuído sob a licença [MIT](LICENSE).
