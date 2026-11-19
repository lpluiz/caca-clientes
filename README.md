# Caça-clientes: a skill do Claude que acha quem precisa do que você vende

Skill grátis para o Claude. Você diz o que vende; ela procura na internet pessoas reclamando, em público, do problema que você resolve, dá uma nota de 0 a 100 para cada uma e escreve uma resposta para você mandar.

Feita pelo canal **Vibe Coding News** (YouTube @vibecodingnews, Instagram @vibecoding.news).

## Como instalar no app do Claude (claude.ai)
1. Baixe o arquivo **caca-clientes.zip** desta página (clique nele e depois em "Download raw file").
2. No Claude, abra **Configurações** e procure a área de **Skills** (em "Capacidades" ou "Personalizar", conforme a versão do app).
3. Clique para **enviar uma skill** e escolha o `caca-clientes.zip`.
4. Pronto. Numa conversa nova, peça: *"acha clientes para o meu negócio: faço sites para pequenas empresas em Brasília"*.

No Claude Code, copie a pasta `caca-clientes` (com o SKILL.md dentro) para `~/.claude/skills/`.

## O que ela faz
1. Entende o seu negócio (pelo link ou pela descrição).
2. Escreve de 8 a 12 frases do jeito que o cliente reclama: busca pela dor, não pelo nome do produto.
3. Busca só em lugares públicos (Reddit, fóruns, X, Reclame Aqui).
4. Abre e confere cada post; nunca inventa link, nome ou data.
5. Dá uma nota de 0 a 100 com critérios abertos.
6. Escreve uma resposta curta que começa com uma dica útil de graça.
7. Entrega a tabela, as respostas e a reclamação que mais se repete.

## Limites, sem enfeite
- A busca da web acha bem fóruns, Reddit e Reclame Aqui. **Instagram e LinkedIn quase não aparecem**, porque essas redes não abrem os posts para a busca.
- Quem reclamou de uma empresa no Reclame Aqui aparece como **"não abordar"**: serve só para entender o que irrita o cliente.
- Quem manda a mensagem é você, uma por uma. Envio em massa é spam, fere as regras das redes e pode bater na LGPD.

## Licença
MIT. Use, adapte e compartilhe.
