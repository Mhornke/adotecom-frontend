# Projeto: Adote.com

Bem-vindo à Wiki oficial do projeto Adote.com. Este documento serve como uma fonte central de informações sobre o projeto, seus objetivos, requisitos e especificações técnicas.

## 1. Visão Geral do Projeto

**Adote.com** é uma plataforma digital projetada para ser uma ponte tecnológica entre animais em situação de abandono e potenciais adotantes. O objetivo é criar um ecossistema intuitivo e confiável que facilite a adoção responsável, centralizando informações de ONGs, abrigos e protetores independentes em um único local acessível.

## 2. O Problema e o Contexto Atual

O Brasil enfrenta um grave problema de superpopulação de animais em situação de vulnerabilidade. A conexão entre quem resgata e quem deseja adotar é muitas vezes ineficiente, resultando em abrigos superlotados e longos períodos de espera para os animais.

- **Cenário Atual:** Milhões de animais vivem abandonados nas ruas ou em abrigos pelo país.
- **Dados de 2024:** Segundo uma matéria da CNN Brasil, mais de 200 mil animais estão sob a tutela de ONGs ou protetores independentes. O Instituto Pet Brasil estima que cerca de **4,8 milhões de cães e gatos** estão em condições de vulnerabilidade no Brasil.
- **Fonte:** [CNN Brasil - Quase 5 milhões de pets estão em situação de vulnerabilidade no Brasil](https://www.cnnbrasil.com.br/nacional/quase-5-milhoes-de-pets-estao-em-situacao-de-vulnerabilidade-no-brasil/)

## 3. Objetivos da Aplicação

1. **Facilitar a Adoção Responsável:** Criar um processo claro e seguro para a adoção de animais em situação de abandono.
2. **Minimizar o Tempo de Espera:** Reduzir o tempo que um animal permanece em um abrigo ou lar temporário até encontrar uma família definitiva.
3. **Promover a Conexão:** Servir como uma ponte direta e eficaz entre animais que precisam de um lar e tutores em potencial.
4. **Centralizar Informações:** Reunir em um único espaço digital animais de diversas ONGs, abrigos e lares temporários de uma determinada localidade.

## 4. Relevância e Impacto Social

A retirada de animais das ruas e a promoção da adoção responsável geram um impacto positivo significativo em diversas áreas da sociedade.

### Saúde Pública

- **Redução de Zoonoses:** Diminui a transmissão de doenças como raiva, leptospirose e toxoplasmose.
- **Diminuição de Acidentes:** Reduz o número de acidentes de trânsito e ataques a pedestres.
- **Controle Populacional:** Ajuda a controlar a reprodução descontrolada de animais de rua.

### Aspecto Ambiental

- **Menor Contaminação:** Reduz a quantidade de lixo revirado e dejetos em vias públicas, que podem contaminar o solo e a água.

### Qualidade de Vida

- **Bem-estar Animal:** Oferece uma vida digna, segura e saudável para os animais.
- **Bem-estar Coletivo:** Promove um ambiente urbano mais limpo, seguro e higiênico para toda a população.

## 5. Público-Alvo e Personas

### Público-Alvo

O Adote.com destina-se a abrigos, ONGs, protetores independentes e cidadãos engajados na causa animal que precisam de uma ferramenta centralizada e eficaz para divulgar animais disponíveis para adoção. A plataforma visa resolver a dificuldade de alcançar um público amplo e organizar o processo de adoção.

### Personas

> Nome: Vanessa
> 
> - **Idade:** 28
> - **Profissão:** Veterinária / Mantenedora de um abrigo temporário
> - **Objetivo:** Encontrar um lar definitivo o mais rápido possível para os animais que resgata.
> - **Frustração:** Dificuldade para encontrar adotantes qualificados e baixo engajamento nas redes sociais do abrigo.
> - **Citação:** *“Eu cuido de muitos animais ao mesmo tempo e, às vezes, é difícil lembrar quem já foi adotado ou quem ainda precisa de cuidados. Seria ótimo ter uma plataforma que me ajudasse a organizar tudo em um só lugar.”*

> Nome: João
> 
> - **Idade:** 26
> - **Profissão:** Atendente de mercado
> - **Objetivo:** Adotar um pet para fazer companhia para seus outros animais de estimação.
> - **Frustração:** Dificuldade em encontrar abrigos próximos e publicações com informações detalhadas e confiáveis sobre os animais.
> - **Citação:** *"Sempre quis adotar um bichinho, mas nunca sei onde procurar ou se ele vai se adaptar à minha rotina. Queria um lugar que mostrasse tudo direitinho, com confiança."*

## 6. Requisitos do Sistema

### Requisitos Funcionais (RF)

- **RF01:** O sistema deve permitir o cadastro de usuários (adotantes e gestores de abrigo).
- **RF02:** Os usuários devem poder visualizar listas de animais disponíveis para adoção.
- **RF03:** O usuário deve poder enviar uma solicitação de adoção para um animal.
- **RF04:** O usuário deve poder visualizar o status de seus pedidos de adoção.
- **RF05:** O usuário deve poder cadastrar animais.
- **RF06:** O gestor de abrigo deve poder aceitar ou recusar solicitações de adoção.

### Requisitos Não Funcionais (RNF)

- **RNF01:** O sistema deve ser responsivo e compatível com celulares, tablets e computadores.
- **RNF02:** O sistema deve garantir a segurança e a confidencialidade dos dados dos usuários.
- **RNF03:** A interface deve ser intuitiva, acessível e fácil de usar.
- **RNF04:** O sistema deve notificar os usuários e gestores sobre as atualizações nos status dos pedidos.
- **RNF05:** O sistema deve ter alta disponibilidade (funcionar 24/7).

### Critérios de Aceite

- **Desempenho:** O tempo de resposta para exibição das listagens de animais deve ser entre 2 e 3 segundos.
- **Carregamento:** O tempo de carregamento das páginas não deve ultrapassar 1 segundo em conexões de 10 Mbps.
- **Usabilidade:** A plataforma deve ser fácil de navegar para todos os perfis de usuário.
- **Confiabilidade:** O sistema deve ser estável e garantir a integridade dos dados.

## 7. Stakeholders

### 🧍‍♂️ Quem Busca (Adotantes)

Pessoas que querem encontrar um animal de estimação de forma simples e segura.

- **Necessidades:** Interface fácil, filtros de busca, informações completas dos animais, processo de adoção simplificado e acompanhamento do pedido.

### 🏠 Quem Anuncia (Abrigos, ONGs, Protetores)

Instituições e pessoas que precisam divulgar animais para adoção de forma organizada e eficaz.

- **Necessidades:** Ferramentas para cadastrar e gerenciar animais, acompanhar pedidos, validar adotantes e obter relatórios.

### ❤️ Quem Apoia (Parceiros, Empresas, Voluntários)

Pessoas e organizações que desejam contribuir com a causa animal.

- **Necessidades:** Transparência no uso do apoio, visibilidade da contribuição, facilidade de contato e acompanhamento do impacto gerado.

## 8. Proposta de Inovação e Integração

Um diferencial do projeto é a integração com o **GestãoProPet**, uma proposta de sistema de gestão de abrigos desenvolvida em paralelo. A integração permitirá que abrigos que utilizam o GestãoProPet publiquem seus animais diretamente na plataforma Adote.com, automatizando a divulgação e ampliando o alcance para encontrar novos lares.

- **Referência:** [Artigo sobre o GestãoProPet](https://www.google.com/search?q=https://medium.com/%40rodrigogastaud97/gest%C3%A3opropet-3d482b4235ac)

## 9. Tecnologias Utilizadas (Tech Stack)

A plataforma Adote.com é construída sobre uma arquitetura moderna, separando as responsabilidades entre o frontend, o backend e os serviços de infraestrutura.

### Frontend (Aplicação Cliente)

- **Framework Principal:** React Native com Expo
- **Linguagem:** TypeScript
- **Navegação:** Expo Router
- **Gerenciamento de Formulários:** React Hook Form
- **Componentes de UI:** React Native Paper
- **Requisições HTTP:** Axios
- **Manipulação de Imagens:**
    - `expo-image-picker`, `expo-file-system`, `expo-image-manipulator` (Mobile)
    - `browser-image-compression` (Web)
- **Armazenamento Local:** AsyncStorage
- **Alertas e Diálogos (Web):** SweetAlert2

**Acessar:**

Front [Adote.com](https://adotecom.vercel.app/)
### Backend (API)

- **Ambiente de Execução:** Node.js
- **Linguagem:** TypeScript
- **Arquitetura:** API RESTful
- **ORM (Object-Relational Mapping):** Prisma
- **Autenticação e Segurança:**
    - JSON Web Tokens (JWT) para gerenciamento de sessões.
    - Bcrypt para hashing de senhas.

**Acessar:**

[API GestãoProPet](https://api-gestao-pro-pet.vercel.app/) 

[API Adote.com](https://adote-com2-0-api.vercel.app/)
### Infraestrutura e Serviços

- **Hospedagem (Frontend e Backend):** Vercel
- **Banco de Dados:** PostgreSQL (hospedado no Neon)
- **Armazenamento de Mídia:** Cloudinary

## 10. Especificação Técnica

### Modelo de Dados

### 🔹 Tabela: `Especie`

- **id:** `INT` (PK)
- **nome:** `VARCHAR`

### 🔹 Tabela: `Animal`

- **id:** `INT` (PK)
- **nome:** `VARCHAR`
- **idade:** `INT`
- **descricao:** `TEXT`
- **porte:** `ENUM('pequeno', 'medio', 'grande')`
- **sexo:** `ENUM('macho', 'femea')`
- **especie_id:** `INT` (FK para `Especie`)
- **abrigo_id:** `INT` (FK para `Abrigo`)

### 🔹 Tabela: `Abrigo`

- **id:** `INT` (PK)
- **nome:** `VARCHAR`
- **descricao:** `TEXT`

### 🔹 Tabela: `Foto`

- **id:** `INT` (PK)
- **descricao:** `VARCHAR`
- **codigoFoto:** `TEXT` (URL da imagem)
- **animal_id:** `INT` (FK para `Animal`)

### 🔹 Tabela: `Usuario`

- **id:** `INT` (PK)
- **nome:** `VARCHAR`
- **email:** `VARCHAR` (UNIQUE)
- **senha:** `VARCHAR`

### 🔹 Tabela: `Pedido`

- **id:** `INT` (PK)
- **resposta:** `ENUM('Aprovado', 'Rejeitado', 'Pendente')`
- **descricao:** `TEXT`
- **animal_id:** `INT` (FK para `Animal`)
- **usuario_id:** `INT` (FK para `Usuario`)

### Diagrama de Caso de Uso

### Atores

- **Usuário/Adotante:** Pessoa que busca um animal para adotar.
- **Gestor (Abrigo/ONG):** Instituição que gerencia os animais.

### Casos de Uso do Usuário

- Registrar-se no sistema.
- Efetuar login.
- Buscar animais por filtros.
- Visualizar detalhes de um animal.
- Solicitar adoção de um animal.
- Acompanhar o status de seus pedidos de adoção.

### Casos de Uso do Gestor

- Adicionar, editar e remover animais do catálogo.
- Visualizar todos os pedidos de adoção recebidos.
- Aprovar ou rejeitar um pedido de adoção.

## 11. Estratégia de Monetização

A sustentabilidade da plataforma será buscada através dos seguintes meios:

### Anúncios

- **Modelo:** Empresas compram espaços de banner na plataforma.
- **Ganhos:** Pagamento mensal por visibilidade (destaque na home, posts patrocinados).

### Plano para Pet Shops

- **Modelo:** Assinatura mensal que oferece maior visibilidade para pet shops, permitindo a publicação de animais e produtos.
- **Ganhos:** Taxa de assinatura e comissão sobre vendas geradas por links/cupons.

### Parcerias Estratégicas

- **Modelo:** Colaboração com empresas, influenciadores, clínicas veterinárias e órgãos públicos (prefeituras, centros de zoonose).
- **Ganhos:** Pagamento por demanda, visibilidade, ou através de ações conjuntas como kits de brindes para adotantes.

## 12. Como Começar (Ambiente de Desenvolvimento)

Para configurar o projeto localmente ou adicionar o repositório a um projeto existente:

```
cd existing_repo
git remote add origin https://gitlab.com/senac-projetos-de-desenvolvimento/2025-dieizon-oliveira-e-matheus-hornke/adote.com.git
git branch -M main
git push -uf origin main

```

## 13. Como Contribuir

Estamos abertos a contribuições! Se você deseja ajudar, por favor, verifique o nosso rastreador de *issues* para ver as tarefas abertas. Para propor uma nova funcionalidade ou correção, crie uma nova *merge request* e descreva as alterações realizadas.

## 14. Metodos
Trabalhamos atrazes da plataforma Miro fazendo o [Diagrama de classes de Uso](https://miro.com/app/board/uXjVIC--7sM=/?share_link_id=762462508036) e [Quadro kanban](https://miro.com/app/board/uXjVIDNQDPY=/)
