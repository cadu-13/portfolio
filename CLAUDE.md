# Portfólio — Carlos Eduardo

Site em HTML único (sem build): canvas de workflow com personagem 3D (Three.js r147).
Publicado na Vercel (deploy automático a partir da `main`): https://portfolio-carloseduardo.vercel.app

## Regras permanentes
- Nunca subir dados, código ou prints da EstrelaBet (nem de nenhum empregador).
- Cases/projetos de exemplo usam apenas dados fictícios.
- Nenhum telefone em material público (site, PDF, README). E-mail público: contato.carloseg@gmail.com.
- Commits com o e-mail noreply do GitHub (cadu-13@users.noreply.github.com).
- `assets/boneco.glb` é carregado direto aqui; a versão "artefato Claude" usa `boneco-modelo.json` (GLB em base64), pois o host não serve .glb.
- Cada repositório tem o seu próprio CLAUDE.md; não misturar projetos.

## Fluxo de trabalho e memória
- Ao concluir qualquer tarefa ou funcionalidade:
  1. Atualizar o "Status Atual" abaixo (máx. 5 linhas), substituindo o conteúdo — o histórico fica no git log.
  2. Rodar testes/linter se existirem; senão, validar abrindo a página (Playwright/screenshot).
  3. Criar um commit atômico em Conventional Commits (ex.: `feat: adiciona login`) e dar push (o container da sessão é descartável).
- Push na `main` publica na Vercel: mudanças grandes/arriscadas vão para uma branch e o Carlos decide quando publicar.
- Nunca apagar regras deste arquivo; apenas atualizar o bloco de status.

## Status Atual
- **Feito:** site no ar na Vercel (workflow + boneco 3D, saudação por horário, contatos, CV em PDF para download).
- **Pendente manual:** preencher o "About" do repo no GitHub (descrição, website, topics) — o proxy bloqueia via API.
- **Próximo passo:** 3 cases com dados fictícios (Radar de Vagas, Minha Carteira, Análise Treinos e Dieta), cada um no seu repo.
