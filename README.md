# blind-spot
Uma premissa de **RPG coop de sobrevivência em tempo real com informação assimétrica** funciona muito bem porque combate o maior problema do gênero: o "efeito passageiro", onde um jogador experiente resolve tudo sozinho enquanto os outros só seguem. Ao distribuir papéis cognitivos distintos mantendo a ação compartilhada, a comunicação verbal entre os jogadores passa a ser a mecânica central.

---

### Visão Geral & Ambientação

* **Gênero:** RPG de Sobrevivência / Ação Tática Cooperativa (1 a 4 jogadores)
* **Câmera:** Top-Down ou Visão Isométrica fluida
* **Tom & Tema:** Expedição em território hostil e desconhecido (ficção científica arcaica, expedição pós-apocalíptica ou fantasia de baixa magia/arqueologia).
* **O Núcleo da Equipe:** Um grupo de especialistas civis e militares que caíram ou ficaram isolados e dependem exclusivamente da sinergia do quarteto para sobreviver.

---

### Aprofundamento dos 4 Papéis

Todos podem andar, coletar recursos básicos, carregar itens e usar ferramentas rudimentares (tochas, picaretas, armas brancas improvisadas). A diferença reside nos **sistemas exclusivos de interface, leitura de mundo e resposta**.

#### 1. O Diplomata / Mediador (Social)

* **Mecânica de Língua:** Textos em tela, placas de sinalização de facções e falas de NPCs aparecem como glifos ilegíveis para os outros três jogadores; apenas o Diplomata vê a tradução legível.
* **Resolução de Conflitos:** Ao encontrar criaturas sencientes, facções territoriais ou facções rivais:
* Abre uma barra de "Tensão/Ameaça".
* Dispõe de opções de negociação em tempo real (oferta de recursos, gestos de submissão, blefe ou intimidação cultural).
* Enquanto os outros mantêm a guarda levantada, o Diplomata atua ditando o tom ("*Não atirem, abaixem as armas e me passem 2 unidades de comida agora*").


* **Visão Social:** Consegue ver a intenção de NPCs (ícones sutis de desconfiança, medo ou agressão iminente).

#### 2. O Operador / Guarda (Combate)

* **Mecânica de Tiro Preciso:** Enquanto os outros jogadores possuem ataques lentos de combate corpo a corpo ou arremesso de pedras/sinalizadores, o Operador tem a mecânica refinada de um *twin-stick shooter* (mira precisa com mouse/analógico, recoil control, recarga rápida e troca de munição).
* **Controle de Área:** Habilidades ativas como armar barricadas portáteis, lançar granadas táticas (luz/fumaça) e disparar tiros supressores que desaceleram hordas.
* **Escudo Humano e Posicionamento:** Pode intervir fisicamente para aparar ataques direcionados aos outros três enquanto estes interagem com terminais ou negociam.

#### 3. O Engenheiro / Decifrador (Lógico)

* **Interação com Quebra-Cabeças:** Terminais eletromecânicos, fechaduras de pressão, válvulas e painéis ancestrais possuem minijogos de lógica (circuitos, sequências harmônicas, alinhamento de engrenagens).
* **Assistência de IA / Interface Aumentada:**
* O Engenheiro possui um visor/dispositivo portátil que projeta conexões lógicas invisíveis aos outros (por exemplo, traça cabos escondidos sob a terra até o gerador correto).
* **Botão de Síntese:** Um recurso com tempo de recarga que solicita à IA uma dedução ("*Elimina 2 conexões erradas*" ou "*Destaca o próximo passo da sequência*").


* **Sobrevivência Técnica:** É quem conserta maquinários do abrigo, veículos e geradores com metade dos recursos e do tempo.

#### 4. O Cartógrafo / Erudito (Conhecimento)

* **Diário de Bordo & Bestiário Automático:** O único com a interface de *Codex* e mapa detalhado. Ao avistar pegadas, marcas em paredes, flora tóxica ou ruínas, o diário registra fraquezas de inimigos, rotas de fuga e pontos de interesse.
* **Banco de Pistas e Cruzamento:** Pode "ticar" duas pistas encontradas no mundo para sintetizar uma descoberta (ex: *Marcas de garras nas árvores* + *Água contaminada* = alerta revelando que o predador da área é cego, mas atraído por sons de água).
* **Comunicação por Pings Avançados:** Consegue marcar no mapa dos companheiros zonas de perigo biológico, rotas seguras e fontes de recursos.

---

### Mecânica de Tag-Team ("Modo Donkey Kong")

Para viabilizar sessões solo ou partidas com 2 a 3 pessoas sem perder a essência do design:

1. **A Caravana / Formação:**
* Os personagens não controlados tornam-se "seguidores ativos" que obedecem a comandos contextuais simples (manter posição, seguir, defender corpo a corpo com faca).


2. **Troca Instantânea de Controle:**
* Um toque em uma tecla (ex: `Q` / `E` ou `1-4`) transfere instantaneamente a câmera e o controle total para outro personagem da fila.
* A interface de usuário (HUD) se adapta imediatamente ao papel assumido (a tela do Diplomata revela o diálogo traduzido; ao mudar para o Guarda, a mira de precisão e as armas de fogo surgem).


3. **Dinâmica em Puzzles e Combates:**
* Jogando em dupla: um jogador controla o Guarda mantendo zumbis afastados enquanto o parceiro alterna rapidamente entre o Engenheiro (abrindo a porta) e o Erudito (consultando a senha no códex).



---

### O Loop de Gameplay

```
Exploração e Coleta 
   └─> Cartógrafo guia a rota e alerta sobre perigos/recursos
        │
        ├─> Encontro com Facção/Criatura
        │    ├─ Opção A: Diplomata negocia passagem ou troca
        │    └─ Opção B: Guarda abre fogo e Engenheiro cerca a área
        │
        └─> Ruína / Dungeon / Travessia
             ├─ Engenheiro resolve a rota lógica
             ├─ Cartógrafo fornece o código/chave de contexto
             └─ Guarda protege a equipe durante a operação

```

---

### Ideias de Diferenciação para Produção

* **Chat de Proximidade com "Estática":** A comunicação oral pode sofrer interferências de tempestades ou distância, tornando o diário do Erudito e os pings do Guarda ferramentas vitais para reagrupar.
* **Fome, Fadiga e Peso:** O Guarda carrega munição pesada e cansa mais rápido; o Diplomata e o Erudito têm mochilas maiores para artefatos e provisões, reforçando a dependência mútua de inventário.
* **Pânico e Estresse:** Se o Guarda for nocauteado, os outros três entram em estado de alerta aumentado (mira treme, visão reduzida), elevando o suspense para que protejam quem os defende.
