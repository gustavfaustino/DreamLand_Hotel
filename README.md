## Sistema de Gerenciamento do Hotel DreamLand

### Visão Geral

O Sistema de Gerenciamento do Hotel DreamLand é uma aplicação web desenvolvida em JavaScript, projetada para auxiliar os funcionários do hotel em suas tarefas diárias. O sistema oferece uma interface simples e intuitiva para gerenciar reservas de quartos, cadastrar e pesquisar hóspedes, calcular custos de abastecimento de veículos e comparar orçamentos para manutenção de ar-condicionado.

### Funcionalidades Principais

- **Reserva de Quartos:**
    - Permite aos funcionários registrar novas reservas de quartos.
    - Verifica a disponibilidade dos quartos antes de confirmar a reserva.
    - Calcula o valor total da hospedagem com base no valor da diária e na quantidade de dias.
    - Permite ao usuário confirmar ou cancelar a reserva.
    - Mantém um registro atualizado da ocupação dos quartos.

- **Cadastro de Hóspedes:**
    - Permite cadastrar hóspedes com nome e idade.
    - Aplica automaticamente gratuidades para hóspedes com menos de 6 anos e meias diárias para hóspedes com mais de 60 anos.
    - Calcula o valor total a ser pago por cada hóspede, considerando as gratuidades e meias diárias.
    - Permite pesquisar hóspedes cadastrados pelo nome.
    - Lista todos os hóspedes cadastrados, exibindo seus dados e o valor a ser pago.

- **Abastecimento de Carros:**
    - **Funcionalidade em desenvolvimento.**

- **Manutenção de Ar-Condicionado:**
    - **Funcionalidade em desenvolvimento.**

### Como Usar

1. **Abra o arquivo `Hotel.html` em seu navegador web.**

2. **Faça login:**
    - Informe seu nome e a senha `2678`.

3. **Navegue pelo menu principal:**
    - Selecione a opção desejada para acessar as diferentes funcionalidades do sistema.

4. **Siga as instruções na tela para cada funcionalidade:**
    - O sistema fornecerá prompts para solicitar as informações necessárias.
    - Mensagens de alerta serão exibidas para confirmar ações ou fornecer feedback ao usuário.

### Estrutura do Código

O código é organizado em funções JavaScript que implementam as diferentes funcionalidades do sistema. As principais funções são:

- `acesso()`: Controla o acesso ao sistema, solicitando nome e senha.
- `inicio()`: Exibe o menu principal e direciona o usuário para a funcionalidade escolhida.
- `reserva_quartos()`: Gerencia as reservas de quartos.
- `opcoes_cadastro()`: Exibe o submenu para cadastro e pesquisa de hóspedes.
- `cadastro_hospedes()`: Permite cadastrar novos hóspedes.
- `pesquisar_hospede()`: Permite pesquisar hóspedes cadastrados.
- `listar_hospedes()`: Lista todos os hóspedes cadastrados.
- `abastecer_carros()`: **Em desenvolvimento.**
- `erro()`: Exibe uma mensagem de erro genérica.
- `sair()`: Permite ao usuário sair do sistema.

### Considerações Finais

- O sistema ainda está em desenvolvimento e algumas funcionalidades estão incompletas.
- O código pode ser adaptado e aprimorado para atender às necessidades específicas do Hotel DreamLand.
- Contribuições e sugestões de melhorias são bem-vindas!

**Esperamos que este sistema ajude a tornar a gestão do Hotel DreamLand mais eficiente e agradável!** 🏨✨
