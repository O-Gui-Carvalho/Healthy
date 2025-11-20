## <a name="introduction">🤖 Introdução</a>

Um aplicativo de gerenciamento de pacientes para a área da saúde que permite que pacientes se registrem facilmente, agendem e gerenciem suas consultas com médicos, incluindo ferramentas administrativas para agendamento, confirmação e cancelamento de consultas, além de notificações por SMS — tudo desenvolvido usando Next.js.

## <a name="tech-stack">⚙️ Técnologias</a>

- Next.js
- Appwrite
- Typescript
- TailwindCSS
- ShadCN
- Twilio

## <a name="features">🔋 Funcionalidades</a>

👉 **Registrar-se como Paciente:** Usuários podem criar uma conta e um perfil pessoal como paciente.

👉 **Agendar Nova Consulta com Médico:** Pacientes podem marcar consultas com médicos conforme sua disponibilidade e podem agendar várias consultas.

👉 **Gerenciar Consultas no Painel Admin:** Administradores podem visualizar e organizar todas as consultas agendadas.

👉 **Confirmar/Agendar Consulta pelo Admin:** Admins podem confirmar e definir horários para garantir o agendamento adequado.

👉 **Cancelar Consulta pelo Admin:** Administradores podem cancelar qualquer consulta quando necessário.

👉 **Enviar SMS na Confirmação da Consulta:** Pacientes recebem notificações por SMS com os detalhes da consulta confirmada.

👉 **Totalmente Responsivo:** O aplicativo funciona perfeitamente em todos os dispositivos e tamanhos de tela.

👉 **Upload de Arquivos com Appwrite Storage:** Usuários podem enviar e armazenar arquivos com segurança usando o armazenamento do Appwrite.

👉 **Monitorar a Performance usando Sentry:** O aplicativo utiliza Sentry para monitorar desempenho e identificar erros.

E muito mais, incluindo arquitetura de código e reutilização.

## <a name="quick-start">🤸 Passo a passo</a>

Siga os passos abaixo para configurar o projeto localmente em sua máquina.

**Pré-requisitos**

Certifique-se de ter o seguinte instalado:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/healthcare.git
cd healthcare
```

**Instalação**

Instale as dependências do projeto:

```bash
npm install
```

**Configurar Variáveis de Ambiente**

Crie um arquivo chamado `.env.local` na raiz do projeto e adicione:

```env
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

Substitua os valores pelos seus dados reais do Appwrite.
Você pode obtê-los ao criar uma conta no [site da Appwrite](https://appwrite.io/).

**Running the Project**

```bash
npm run dev
```

Abra [http://localhost:3000](http://localhost:3000) no navegador para visualizar o projeto.
