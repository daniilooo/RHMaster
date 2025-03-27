# RHMaster - Sistema de Gestão de Recursos Humanos

O **RHMaster** é um sistema modular de Recursos Humanos desenvolvido em **Laravel**. O sistema visa facilitar a gestão de funcionários, folha de pagamento, recrutamento e seleção, avaliações de desempenho, e muito mais, tudo de maneira segura, automatizada e eficiente.

## Funcionalidades

### 1. **Gestão de Funcionários**
- Cadastro, edição e exclusão de funcionários.
- Controle de jornada de trabalho e horas extras.
- Gerenciamento de férias, afastamentos e licenças.
- Registro de desligamentos (rescisão).
- Envio de documentos digitais com armazenamento seguro no servidor.
- Controle de documentos com histórico de versões e validade.

### 2. **Gestão de Cargos e Setores**
- Cadastro de cargos com responsabilidades e requisitos.
- Organização dos funcionários por setor.
- Definição de plano de carreira e promoções.

### 3. **Folha de Pagamento**
- Cálculo automático de salários, descontos e benefícios.
- Geração de holerites e envio automatizado para os funcionários.
- Integração com sistema bancário para pagamento de salários.

### 4. **Recrutamento e Seleção**
- Cadastro de vagas de emprego e descrição dos cargos.
- Recebimento e triagem de currículos.
- Agendamento de entrevistas e avaliações dos candidatos.
- Registro completo do processo seletivo.

### 5. **Avaliação de Desempenho**
- Definição de tipos de avaliação (periódica, 360°, autoavaliação, etc.).
- Definição de critérios de avaliação e registro de feedbacks.
- Geração de relatórios de desempenho e sugestões de treinamento.

### 6. **Controle de Acessos e Permissões**
- Definição de níveis de acesso (administrador, RH, gestores e funcionários).
- Controle de visualização de informações confidenciais.
- Logs de acesso para auditoria.

### 7. **Comunicação Interna**
- Envio de comunicados internos para os funcionários.
- Agendamento de reuniões e eventos internos.
- Chat interno para comunicação rápida.

### 8. **Relatórios e Métricas**
- Geração de relatórios sobre folha de pagamento, absenteísmo, turnover, etc.
- Dashboard para gestores com indicadores chave.

## Tecnologias Utilizadas
- **Backend**: Laravel 9.x (PHP)
- **Banco de Dados**: MySQL
- **Autenticação**: Laravel Passport (OAuth2)
- **Armazenamento de Arquivos**: Sistema de arquivos local (pode ser configurado para armazenamento em nuvem)
- **Frontend**: A ser decidido (React, Vue.js, Angular)
- **App Mobile**: A ser decidido (Flutter, React Native)

## Estrutura do Repositório

```bash
rhmaster/
├── app/                   # Código do backend (Controllers, Models, etc.)
├── database/              # Migrations, seeders e factories
├── public/                # Arquivos públicos (CSS, JS, imagens, etc.)
├── resources/             # Views, arquivos de tradução, etc.
├── routes/                # Definição das rotas da aplicação
├── storage/               # Armazenamento de arquivos (documentos dos funcionários)
└── tests/                 # Testes da aplicação

Contato
Desenvolvido por Danilo Franco.
Email: engdanilofranco@gmail.com