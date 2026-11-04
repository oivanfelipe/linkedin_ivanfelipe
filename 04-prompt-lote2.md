# Prompt do Claude in Chrome: Lote 2 (SEO e marketing de consumo)

Cole o bloco abaixo no Claude in Chrome, com o Chrome logado no LinkedIn. Rode em um dia diferente do lote 1.

---

## PROMPT

Você vai me ajudar a coletar posts públicos de 3 perfis do LinkedIn para uma análise de conteúdo (hooks, formatos, engajamento). Aja como uma pessoa lendo com calma, não como um robô.

### Regras de segurança (obrigatórias)
1. SOMENTE LEITURA. Não curta, não comente, não reaja, não compartilhe, não siga, não conecte, não envie mensagem, não publique nada. Não clique em nenhum botão de ação.
2. Não use busca avançada, não exporte listas, não abra Sales Navigator.
3. Processe os 3 perfis abaixo, um de cada vez, e no máximo 15 posts originais recentes por perfil.
4. Espere de 20 a 40 segundos entre uma página e outra e role a página devagar. Espere 2 a 3 minutos ao trocar de perfil.
5. Se aparecer captcha, pedido de verificação de segurança, aviso de uso incomum ou pedido para logar de novo: PARE na hora, não tente resolver, e me avise.
6. Não acesse conteúdo que exija conexão ou que esteja bloqueado.

### O que fazer, para cada perfil
1. Abra o perfil pela URL indicada. Confirme que é a pessoa certa (headline e área). Se não for, pare e me avise antes de continuar.
2. Registre: nome, link, headline, seguidores, localização, empresa atual.
3. Abra "Atividade" > "Posts" e leia os últimos 15 posts originais (ignore reposts e comentários).
4. Para cada post, registre exatamente:
   - link do post
   - data (ou "há X semanas")
   - formato: texto, imagem, carrossel/documento (com nº de páginas), vídeo, enquete, artigo ou link
   - primeira linha completa (o hook), copiada literalmente
   - texto completo, copiado literalmente (clique em "ver mais" para expandir)
   - número de caracteres aproximado
   - reações, comentários, compartilhamentos (os números visíveis)
   - se tem link externo no corpo
   - chamada para ação final (copiar a última frase)
   - se o post tem número, resultado ou dado concreto no hook (sim/não e qual)
   - se foi publicado em grupo ou é post patrocinado (anote, pois distorce o engajamento)
   - se há tema ou série recorrente (só se for óbvio)
5. Em carrossel, anote o número de slides e o tema do primeiro slide. Não precisa transcrever os slides.
6. Se o autor colocou algo no primeiro comentário (link, CTA), anote em uma linha.
7. Não invente nem estime nada que você não viu. Se um dado não aparecer, escreva "não visível".

### Formato de entrega
Ao final de cada perfil, devolva uma tabela em Markdown, uma linha por post, com as colunas:
`link | data | formato | hook | caracteres | reações | comentários | compartilhamentos | link externo | CTA | dado concreto no hook | grupo/patrocinado`
e, logo abaixo, o texto completo dos posts numerados na mesma ordem.
No fim de todos os perfis, escreva uma observação curta sobre qualquer bloqueio ou aviso que apareceu.

### Perfis do lote 2
1. Diego Ivo, CEO da Conversion (SEO): https://www.linkedin.com/in/diegoivo/
2. Daniel Imamura, Head de SEO do Grupo Duo&Co: https://www.linkedin.com/in/danielimamura/
3. Murilo Moreno, consultor de marketing e professor da ESPM: https://www.linkedin.com/in/murilomoreno/

---

## Por que estes três
- Diego Ivo e Daniel Imamura são de SEO, o seu nicho. Permitem testar se o "dado concreto" aparece nos hooks de quem fala de performance.
- Murilo Moreno é marca e consumo, com Top Voice. Serve de contraponto de formato.
- Os campos novos (dado concreto no hook, grupo/patrocinado) vêm da análise do lote 1.
