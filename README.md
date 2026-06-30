# Informativos Escolares

## Plataforma Web para Gerenciamento de Informativos e Projetos Educacionais

---

# Sobre o Projeto

O **Informativos Escolares** é uma plataforma web desenvolvida para centralizar a comunicação entre a instituição de ensino e as famílias dos alunos.

O sistema foi idealizado para facilitar o acesso a informativos, projetos pedagógicos, comunicados, eventos e notícias, promovendo maior transparência e participação dos responsáveis no processo educacional.

A plataforma permite que pais e responsáveis acompanhem as atividades da instituição por meio de um ambiente digital moderno, enquanto a equipe administrativa possui ferramentas para gerenciar todo o conteúdo publicado.

---

# Objetivo

Desenvolver uma plataforma web responsiva para gerenciamento e divulgação de:

* Informativos escolares;
* Projetos pedagógicos;
* Comunicados institucionais;
* Notícias e eventos.

Promovendo uma comunicação mais eficiente entre a instituição e as famílias.

---

# Funcionalidades

## Pais e Responsáveis

* Login no sistema;
* Visualização de informativos;
* Acompanhamento de projetos pedagógicos;
* Consulta de notícias e comunicados;
* Visualização de imagens e documentos;
* Acesso ao histórico de publicações.

---

## Administradores

* Login administrativo;
* Cadastro de informativos;
* Edição de publicações;
* Exclusão de publicações;
* Cadastro de projetos pedagógicos;
* Atualização de conteúdos dos projetos;
* Upload de imagens e documentos;
* Gerenciamento completo do sistema.

---

# Arquitetura do Sistema

## Fluxo de Acesso

### Login dos Pais e Responsáveis

1. Acessar a página inicial;
2. Informar as credenciais;
3. O sistema valida os dados;
4. Redirecionamento para a página principal;
5. Exibição dos informativos e projetos.

### Login dos Administradores

1. Acessar a página inicial;
2. Informar as credenciais administrativas;
3. O sistema valida os dados;
4. Redirecionamento para o painel administrativo;
5. Exibição das funcionalidades de gerenciamento.

---

# Módulos do Sistema

## Informativos

Permite:

* Publicação de notícias;
* Divulgação de eventos;
* Compartilhamento de comunicados;
* Inserção de imagens;
* Inclusão de documentos;
* Organização cronológica das postagens.

---

## Projetos Pedagógicos

Permite:

* Cadastro de projetos;
* Organização em categorias;
* Atualizações periódicas;
* Upload de fotos;
* Upload de vídeos;
* Compartilhamento de documentos;
* Histórico de desenvolvimento.

---

# Tecnologias Utilizadas

* React
* HTML5
* CSS3
* Node.js
* MongoDB

---

# Padrões de Projeto (Design Patterns)

Durante o desenvolvimento foram implementados os seguintes padrões de projeto:

* **Facade (Fachada):** simplifica a comunicação entre os módulos do sistema por meio de uma interface unificada.
* **Factory (Fábrica):** utilizado para criação de objetos de forma organizada e desacoplada.
* **Singleton:** garante a existência de uma única instância para componentes compartilhados da aplicação.

---

# Responsividade

A plataforma foi projetada para funcionar em:

* Computadores;
* Tablets;
* Smartphones.

Garantindo acessibilidade para todos os usuários.

---

# Segurança

O sistema considera:

* Controle de acesso por perfil;
* Autenticação de usuários;
* Proteção de dados;
* Backup das informações;
* Armazenamento seguro de arquivos;
* Conformidade com a LGPD (Lei Geral de Proteção de Dados).

---

# Diferenciais

* Comunicação centralizada;
* Interface simples e intuitiva;
* Acompanhamento de projetos em tempo real;
* Redução do uso de comunicados impressos;
* Transparência das ações institucionais;
* Compatibilidade com dispositivos móveis.

---

# Impacto Esperado

A implementação do **Informativos Escolares** contribuirá para:

* Fortalecimento da relação entre instituição e famílias;
* Maior participação dos responsáveis;
* Divulgação eficiente de projetos pedagógicos;
* Melhor organização das informações institucionais;
* Modernização dos canais de comunicação.

---

# Requisitos do Sistema

## Funcionais

* Autenticação de usuários;
* Controle de acesso por perfil;
* CRUD de informativos;
* CRUD de projetos;
* Upload de arquivos e imagens;
* Visualização de conteúdos.

## Não Funcionais

* Segurança;
* Responsividade;
* Usabilidade;
* Escalabilidade;
* Disponibilidade;
* Conformidade com a LGPD.

---

# Como Rodar o Projeto

## 1. Clonar o Repositório

```bash
git clone <URL_DO_REPOSITORIO>
cd Informativos-Escolares
```

---

## 2. Instalar Dependências

```bash
npm install
```

---

## 3. Configurar Variáveis de Ambiente

Crie um arquivo `.env` na raiz do projeto:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/informativos-escolares
JWT_SECRET=informativos_escolares_2026
```

---

## 4. Iniciar o MongoDB

Execute:

```bash
mongod
```

Ou utilize uma instância do MongoDB Atlas alterando a variável `MONGO_URI`.

---

## 5. Rodar o Projeto

```bash
npm run dev
```

### Backend

```text
http://localhost:5000
```

### Frontend

```text
http://localhost:5173
```

---

# Scripts Disponíveis

### Iniciar aplicação

```bash
npm run dev
```

### Backend

```bash
npm run backend
```

### Frontend

```bash
npm run frontend
```

---

# Status do Projeto

🚧 Em desenvolvimento.

---

# Autor

**Alice Santos M. de Barros**

### Créditos

Agradecimentos a **José Antonio de Carvalho Neto** e à **Manuela Antonelli** pela ideia do projeto e colaboração na elaboração dos requisitos funcionais.

---

# Atividade Acadêmica

Este projeto foi desenvolvido como **atividade final da disciplina de Engenharia de Software**, aplicando conceitos de análise de requisitos, arquitetura de software, desenvolvimento web, banco de dados e padrões de projeto.

---

# Licença

Este projeto possui finalidade exclusivamente acadêmica e educacional.

