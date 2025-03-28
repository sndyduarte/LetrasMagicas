![WhatsApp Image 2025-03-28 at 10 46 36](https://github.com/user-attachments/assets/5bcf335b-f544-415f-baae-8494cbbf4bb4)

# Sumário


Planejamento

Requisitos

Desenvolvimento

MVP

Scrum

# 1. Planejamento


    1.1 Objetivo

Desenvolver um aplicativo interativo para auxiliar na alfabetização de crianças de 6 a 10 anos, utilizando uma abordagem gamificada com uma trilha de caminhada para aprendizado e um sistema de banco de dados para monitorar o progresso.


    1.2 Justificativa

A alfabetização é uma etapa essencial no desenvolvimento infantil, e o uso de tecnologia pode tornar esse processo mais dinâmico e envolvente. O formato gamificado incentiva a aprendizagem de maneira lúdica e personalizada, estimulando o engajamento das crianças.


    1.3 Metodologia

● Desenvolvimento iterativo baseado na metodologia ágil (Scrum).

● Pesquisa com pedagogos para validar a eficácia do método de ensino.

● Testes com usuários (crianças dentro da faixa etária e docentes) para aprimoramento.


# 2. Requisitos

  
    2.1 Requisitos Funcionais


● Cadastro de alunos e responsáveis.

● Trilha de caminhada interativa, onde cada etapa representa um nível de aprendizado.

● Exercícios interativos de leitura, escrita e pronúncia.

● Sistema de recompensas e conquistas para incentivar o progresso.

● Banco de dados para armazenar o desempenho do aluno.

● Relatórios de evolução acessíveis aos pais e professores.


    2.2 Requisitos Não Funcionais


● Interface colorida e intuitiva, voltada para o público infantil.

● Suporte para dispositivos móveis (Android e iOS).

● Tempo de resposta inferior a 2 segundos por interação.

● Segurança dos dados dos alunos e responsáveis.


# 3. Desenvolvimento


    3.1 Tecnologias Utilizadas


● Frontend: Flutter para desenvolvimento multiplataforma.

● Backend: Node.js com Express.js para gerenciar lógica de negócios.

● Banco de Dados: Firebase Firestore (dados dinâmicos, progresso e interações) e PostgreSQL (dados permanentes como cadastro e estatísticas).

● Inteligência Artificial: Whisper (gratuito, mas pesado) ou Google Speech-to-Text API (custo) para reconhecimento de voz.

● Hospedagem: Firebase Hosting e AWS para escalabilidade e backups automáticos.

● Segurança: Firebase Authentication para login de alunos e responsáveis, criptografia de informações sensíveis, restrição de acessos e termo de consentimento para armazenamento dos dados.


# 4. MVP (Produto Mínimo Viável)


    4.1 Funcionalidades Entregues


● Trilha de aprendizagem com fases progressivas.

● Exercícios básicos de leitura e escrita.

● Sistema de progresso e conquistas.

● Dashboard para pais e professores acompanharem o desempenho.

● Design interativo e adequado para crianças.


    4.2 Limitações


● Apenas o idioma português na versão inicial.

● Modelos básicos de reconhecimento de voz.

● Disponibilidade inicial apenas para Android.


# 5. Scrum - Planejamento dos Sprints


    Sprint 1 – Configuração do Ambiente e Banco de Dados
Configurar Firebase Firestore para progresso dos alunos Configurar PostgreSQL para dados permanentes (cadastro, estatísticas) Implementar Firebase Authentication para login de alunos e responsáveis Criar o Termo de Consentimento para pais/responsáveis
  
    Sprint 2 – Interface e Fluxo Principal
Criar tela de login e gerenciamento de contas Criar a tela principal com a trilha de aprendizado Criar os primeiros exercícios de leitura e escrita Implementar segurança nos dados (criptografia de informações sensíveis)

    Sprint 3 – Interatividade e Sistema de Feedback
Implementar sistema de recompensas e conquistas Criar a dashboard para pais e professores acompanharem o progresso Implementar feedback interativo nos exercícios Definir o modelo de IA para reconhecimento de voz (Whisper ou Google Speech-to-Text)

    Sprint 4 – Implementação do Reconhecimento de Voz
Configurar a IA para avaliar pronúncia das crianças Ajustar o sistema de feedback para personalizar dicas baseadas no desempenho Criar um modelo básico de aprendizado para identificar dificuldades

    Sprint 5 – Testes e Otimizações
Testes de usabilidade com crianças e pais Melhorias no design e performance do app Implementação de backups automáticos (Firebase e AWS) Ajustes de segurança para garantir privacidade dos dados

    Passos Incrementais

● Após a Sprint 5, iniciar melhorias baseadas no feedback dos usuários.

● Planejar a expansão para iOS na versão futura.
