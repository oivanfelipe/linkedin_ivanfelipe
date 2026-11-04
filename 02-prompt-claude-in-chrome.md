# Prompt para o Claude in Chrome: coleta de posts (volume baixo)

Cole o bloco abaixo no Claude in Chrome, com o Chrome logado no LinkedIn.
Rode em lotes: lote 1 (piloto, 3 perfis) hoje; lotes seguintes de 3 a 4 perfis, em dias diferentes.

---

## PROMPT

Você vai me ajudar a coletar posts públicos de alguns perfis do LinkedIn para uma análise de conteúdo (hooks, formatos, engajamento). Aja como uma pessoa lendo com calma, não como um robô.

### Regras de segurança (obrigatórias)
1. SOMENTE LEITURA. Não curta, não comente, não reaja, não compartilhe, não siga, não conecte, não envie mensagem, não publique nada. Não clique em nenhum botão de ação.
2. Não use busca avançada, não exporte listas, não abra Sales Navigator.
3. Processe no máximo 3 perfis por sessão. Por perfil, colete no máximo 15 posts recentes.
4. Espere de 20 a 40 segundos entre uma página e outra e role a página devagar. Espere 2 a 3 minutos ao trocar de perfil.
5. Se aparecer captcha, pedido de verificação de segurança, aviso de uso incomum ou pedido para logar de novo: PARE na hora, não tente resolver, e me avise.
6. Não tente acessar posts de perfis privados ou conteúdo que exija conexão.

### O que fazer, para cada perfil da lista
1. Pesquise o nome na busca do LinkedIn (ou abra o perfil, se eu der o link) e confirme que é a pessoa certa (cargo/área de marketing). Se houver dúvida entre homônimos, me pergunte antes de continuar.
2. Registre do perfil: nome, link, headline, número de seguidores, localização.
3. Abra a seção "Atividade" > "Posts" e leia os últimos 15 posts originais (ignore reposts e comentários).
4. Para cada post, registre exatamente:
   - link do post
   - data (ou "há X semanas")
   - formato: texto, imagem, carrossel/documento, vídeo, enquete, artigo ou link
   - primeira linha completa (o hook), copiada literalmente
   - texto completo do post, copiado literalmente (clique em "ver mais" para expandir)
   - número de caracteres aproximado
   - reações, comentários, compartilhamentos (os números visíveis)
   - se tem link externo no corpo
   - chamada para ação no final (copiar a última frase)
   - se há tema/série recorrente (anote só se for óbvio)
5. Para posts em carrossel, anote o número de slides e o tema do primeiro slide. Não precisa transcrever os slides.
6. Não invente nem estime nada que você não viu. Se um dado não aparecer, escreva "não visível".

### Formato de entrega
Ao final de cada perfil, devolva uma tabela em Markdown com uma linha por post e as colunas:
`link | data | formato | hook | caracteres | reações | comentários | compartilhamentos | link externo | CTA`
e, logo abaixo, o texto completo dos posts numerados na mesma ordem.
Depois do último perfil, escreva uma observação curta sobre qualquer bloqueio ou aviso que apareceu.

### Perfis do lote 1 (piloto)
1. Victor Wendt
2. João Branco
3. Priscila Mendes (estrategista de LinkedIn e posicionamento)

---

## Lista candidata para os próximos lotes (validar antes)

Retirada de rankings públicos (Favikon, Magicpost). Não confirmei que os nomes pertencem ao nicho exato; confirme a área antes de rodar.

| Lote | Perfil | Origem |
|---|---|---|
| 2 | Renato Camargo | Favikon, marketing |
| 2 | Murilo Moreno | Favikon, marketing |
| 2 | Michel Jasper | Favikon, LinkedIn Brasil |
| 3 | André Santos | Favikon, LinkedIn Brasil |
| 3 | Diego Ivo (Conversion) | Favikon, SEO |
| 3 | Daniel Imamura | Favikon, SEO |
| 4 | Gabriel Sguarizi Panceri | Favikon, SEO |
| 4 | Fábio Ricotta | mLabs, tráfego pago (lista com possíveis erros) |

Depois de cada lote, cole o resultado aqui na conversa com o Claude da análise (ou salve em um arquivo na pasta do projeto).
