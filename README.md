# SOS Clean House

O projeto consiste no desenvolvimento de um sistema para gerenciar agendas de prestadores de serviços de limpeza autônomos, como diaristas e faxineiras. A plataforma permitirá que esses profissionais cadastrem seus horários disponíveis, valores, locais de atendimento e bloqueiem datas específicas para auto controle da agenda. As contratações e os pagamentos ocorrerão diretamente pelo sistema.
Na área do cliente, será possível criar uma conta, cadastrar endereços e meios de pagamento, buscar profissionais disponíveis próximos à sua localização, visualizar avaliações e comentários, além de deixar feedback sobre os serviços prestados. Para aumentar a segurança, o sistema contará com uma seção de antecedentes criminais dos prestadores.
O sistema permitirá o cadastro de combos de produtos de limpeza, para que os profissionais possam levá-los ao local do serviço, agregando ainda mais praticidade para o cliente.
O sistema terá atualizações constantes como novas funcionalidades, ajustes de bugs ...

# Sprints

## Sprint 1: Definição do escopo e estruturação do projeto (UML)
### O que foi feito:
- Definição completa do escopo do sistema.
- Levantamento de requisitos funcionais e não funcionais.
- Criação dos diagramas UML: casos de uso, classes e sequência.
- Organização da estrutura inicial do projeto.
- Explicação da estrutura para o grupo.
### Desenvolvedor: Jaíne.
### Período:  05/08/2025 a 17/08/2025

## Sprint 2: Modelagem e criação do banco de dados
### O que foi feito:
- Modelado o banco de dados com base nos diagramas da Sprint anterior.
- Criadas as entidades principais e relacionamentos.
- Banco validado com PostgreSQL.
### Desenvolvedor: João.
### Período: 17/05/2025 a 25/05/2025
- Período de testes: 1 dia
- Período de revisão: 1 dia
- Período de deploy: 1 dia

## Sprint 3: Configuração do ambiente de desenvolvimento (Back e Front)
### O que foi feito:
- Configurado o ambiente local com Spring Boot e Angular.
- Instalação de dependências e ferramentas de controle de versão.
- Repositórios conectados ao GitHub.
### Desenvolvedor: João e André.
### O que cada desenvolvedor fez:
-	João: Configurou o Angular, criou o template inicial e componentes base.
-	André: Configurou o back-end com Spring Boot e conexão com o banco de dados.

### Período: 25/05/2025 a 02/06/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

## Sprint 4: Desenvolvimento da autenticação de usuários
### O que foi feito:
- Implementado formulário de login com campos de e-mail e senha.
- Adicionada a opção de login via Google e Microsoft.
- Métodos no backend: autenticarFormulario, autenticarGoogle e autenticarMicrosoft
### Desenvolvedor: Jaíne.
### Período: 19/05/2025 a 01/06/2025
- Período de testes: 2 dia
- Período de revisão: 1 dia
- Período de deploy: 1 dia

##  Sprint 5: Criação das entidades principais do sistema
### O que foi feito:
- Implementadas as entidades: Usuario, Cliente, Prestador, Endereco, Servico etc.
- Regras de negócio iniciais implementadas.
- Entidades integradas com o banco de dados com sucesso.
- João não faz mais parte da equipe.
- Pausa no projeto por demanda de outro cliente.
### Desenvolvedor: André e Jaíne.
### Período: 03/06/2025 a 11/06/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

# Faltam fazer

##  Sprint 6: Cadastro e Consulta de Disponibilidade
### O precisa ser feito:
-	Formulário para prestadores informarem dias e horários disponíveis
-	Consulta de disponibilidade por clientes
-	Lógica de agendamento e de horários.
### Desenvolvedor: André e Jaíne.
### Período: 03/09/2025 a 09/09/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

## Sprint 7: Sistema de Agendamento
### O precisa ser feito:
-	Lógica para clientes agendarem serviços com base na disponibilidade
-	Atualização de agenda do prestador automaticamente
### Desenvolvedor: André e Jaíne.
### Período: 09/09/2025 a 16/09/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

## Sprint 8: Tela inicial, de login e Segurança com JWT
### O precisa ser feito:
-	Tela inicial do sistema
-	Tela de login para prestador e cliente
- Autenticação e autorização com tokens JWT
### Desenvolvedor: André e Jaíne.
### Período: 17/09/2025 a 20/09/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

## Sprint 9: Chat entre Cliente e Prestador
### O precisa ser feito:
-	Chat básico com envio de mensagens entre cliente e prestador
-	Armazenamento no banco por agendamento
### Desenvolvedor: André e Jaíne.
### Período: 24/09/2025 a 27/09/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia


## Sprint 10: Avaliação de Serviços
### O precisa ser feito:
-	Sistema de avaliação dos prestadores por parte dos clientes
-	Tela para clientes avaliarem os serviços após o agendamento concluído.
-	Cálculo automático da média de avaliações por prestador.
-	Visualização pública das avaliações e comentários.
### Desenvolvedor: André e Jaíne.
### Período: 01/10/2025 a 04/10/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

## Agendamento com o cliente para mostrar os resultados 06/10/2025

##  Sprint 11: Cadastro e Gerenciamento de Endereços com Integração API
### O precisa ser feito:
-	Implementação do cadastro de endereços pelos clientes.
-	Integração com API externa para busca automática de endereço via CEP.
-	Validação de campos e edição de endereços
### Desenvolvedor: André e Jaíne.
### Período: 08/10/2025 a 12/10/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##   Sprint 12: Cadastro e Gestão de Meios de Pagamento via APIs
### O precisa ser feito:
-	Cadastro e armazenamento seguro de meios de pagamento dos clientes (cartões, etc).
-	Integração com API de pagamento (Stripe, MercadoPago) para transações.
-	Tela para adicionar, editar e remover métodos de pagamento.
### Desenvolvedor: André e Jaíne.
### Período: 16/10/2025 a 23/10/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##   Sprint 13: Sistema de Notificações
### O precisa ser feito:
- Implementação de notificações para clientes e prestadores: confirmação de agendamento, lembretes, cancelamentos.
-	Notificações por e-mail e push.
### Desenvolvedor: André e Jaíne.
### Período: 24/10/2025 a 30/10/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##   Sprint 14: Busca por Prestadores por Geolocalização
### O precisa ser feito:
-	Integração com API de geolocalização para localização de prestadores próximos ao cliente.
-	Exibição dos prestadores em mapa e lista ordenada por proximidade.
### Desenvolvedor: André e Jaíne.
### Período: 31/10/2025 a 07/11/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##  Sprint 15: Filtros Avançados na Busca
### O precisa ser feito:
-	Implementação de filtros por preço, avaliação, tipo de serviço, distância e disponibilidade.
-	Combinação de múltiplos filtros com atualização dos resultados.
### Desenvolvedor: Jaíne.
### Período: 08/11/2025 a 15/11/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##  Sprint 16: Histórico de Pagamentos e Caixa para Prestadores
### O precisa ser feito:
-	Implementação de filtros por preço, avaliação, tipo de serviço, distância e disponibilidade.
-	Combinação de múltiplos filtros com atualização dos resultados.
### Desenvolvedor: André.
### Período: 08/11/2025 a 15/11/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##  Sprint 17: Sistema de Upload e Validação de Antecedentes Criminais
### O precisa ser feito:
-	Tela para prestadores fazerem upload de documentos de antecedentes criminais.
-	Backend para validação e armazenamento seguro dos documentos.
-	Regras para bloqueio automático do perfil em caso de pendências ou divergencias.
### Desenvolvedor: André e Jaíne.
### Período: 24/11/2025 a 01/12/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

## Agendamento com o cliente para mostrar os resultados 02/12/2025

##   Sprint 18: Sistema de Avaliações e Comentários Pós-Serviço
### O precisa ser feito:
-	Tela para clientes avaliarem os serviços após o agendamento concluído.
-	Cálculo automático da média de avaliações por prestador.
-	Visualização pública das avaliações e comentários.
### Desenvolvedor: André e Jaíne.
### Período: 02/12/2025 a 09/12/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##   Sprint 19: Conferência de tudo o que já foi feito
### O precisa ser feito:
-	Conferencia e testes de tudo o que já foi implementado
### Desenvolvedor: André e Jaíne.
### Período: 10/12/2025 a 17/12/2025

##  Sprint 20: Página Inicial e Navegação Intuitiva (UX/UI)
### O precisa ser feito:
-	Design e implementação da página inicial com destaque para busca, promoções e perfis recomendados.
-	Melhorias na Navegação para clientes e prestadores.
-	Ajustes para responsividade em dispositivos móveis.
### Desenvolvedor: André e Jaíne.
### Período: 18/12/2025 a 22/12/2025
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##  Sprint 21: Cadastro e Gerenciamento de Combos de Produtos
### O precisa ser feito:
-	Tela para prestadores cadastrarem combos de produtos (ex: kit de limpeza para levar no serviço).
-	Gestão de estoque básico e preços dos combos.
-	Associação dos combos aos agendamentos.
### Desenvolvedor: André e Jaíne.
### Período: 04/01/2025 a 10/01/2026
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia


##  Sprint 22: Painel Administrativo - Gestão de Reservas e Agendamentos
### O precisa ser feito:
-	Implementação da funcionalidade para visualização e edição das reservas feitas pelos clientes.
-	Ferramentas para cancelamento, reprogramação e análise de agendamentos.
### Desenvolvedor: André e Jaíne.
### Período: 11/01/2026 a 18/01/2026
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##  Sprint 23: Painel Administrativo - Gestão Financeira e Relatórios
### O precisa ser feito:
-	Dashboard financeiro para acompanhamento das receitas e despesas do sistema.
-	Geração de relatórios customizados por data, meses.
### Desenvolvedor: André e Jaíne.
### Período: 19/01/2026 a 26/01/2026
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

##  Sprint 24: Testes Finais, Correções e Deploy Final
### O precisa ser feito:
-	Testes integrados em todo o sistema, correção de bugs e otimizações finais.
-	Preparação para deploy em ambiente de produção.
-	Documentação final do projeto e treinamento da equipe
### Desenvolvedor: André e Jaíne.
### Período: 27/01/2026 a 03/02/2026
- Período de testes: 1 dia
- Período de revisão: 2 dia
- Período de deploy: 1 dia

## Lançamento em 11/02/2026


# Material para estudo do projeto
## Protótipos

<img width="1051" height="1075" alt="{377C62EC-A1ED-4ADD-9A1E-F537FEEA5DAF}" src="https://github.com/user-attachments/assets/6050c9c0-0652-4668-a493-90304c004bd8" />
<img width="575" height="586" alt="{4E0487B4-0ADF-4F19-897D-46D349543053}" src="https://github.com/user-attachments/assets/340b02a9-0b5d-4752-97e6-6728e9558152" />
<img width="581" height="578" alt="{C4A8F362-08E8-492A-8D4A-D64754A8D2BB}" src="https://github.com/user-attachments/assets/029dfd70-361a-4a10-bd0e-518c167d4a5b" />
<img width="669" height="584" alt="{AAE25EEE-6462-4758-BD62-8F73F84B7B8E}" src="https://github.com/user-attachments/assets/8e78c327-d97a-43c5-9eb1-6a16575e76f3" />
<img width="406" height="578" alt="{667C9AF0-B16B-4491-A26D-A9513BAB3812}" src="https://github.com/user-attachments/assets/8c6e8c28-5b13-4b48-b74b-340478256ac4" />

## Tela de agendamento será dividida em várias partes. (Tela explicativa do profissional / Tela de escolha data e hora / Tela de endereço)

<img width="278" height="520" alt="{2B109A17-7657-46FE-937A-5EAEAC104447}" src="https://github.com/user-attachments/assets/d8c39467-b241-41b3-a880-c48062166bfe" />

## Ideia de calendário para o prestador, sendo possível bloquear os dias no qual o prestador não irá trabalhar.

<img width="586" height="526" alt="{D7D005EB-AB39-496B-9D8B-BA7C60A58DBD}" src="https://github.com/user-attachments/assets/1cdba136-f27e-4a03-8598-b2c7b3955659" />


