EconomiaAddon/
├── behavior_packs/
│   └── Economia_Behavior/
│       ├── functions/
│       │   ├── moedas/
│       │   │   ├── converter_itens.mcfunction   # Fornalha: conversão de itens em moedas
│       │   │   └── trocar_moedas.mcfunction     # Troca entre moedas (ex: 100 esmeraldas = 1 cobre)
│       │   ├── npcs/
│       │   │   ├── spawn_npcs.mcfunction        # Gerar NPCs em estruturas
│       │   │   ├── minerador.mcfunction         # Comportamento do Minerador
│       │   │   └── banqueiro.mcfunction         # Comportamento do Banqueiro
│       │   └── lojas.mcfunction                 # Sistema de lojas/trocas
│       ├── entities/
│       │   ├── minerador.json                   # Entidade customizada do Minerador
│       │   └── banqueiro.json                   # Entidade customizada do Banqueiro
│       ├── loot_tables/
│       │   ├── minerador_drops.json             # Tabela de drops do Minerador
│       │   └── banqueiro_drops.json             # Tabela de drops do Banqueiro
│       └── manifest.json
└── resource_packs/
    └── Economia_Resources/
        ├── textures/
        │   └── items/
        │       ├── emerald_coin.png             # Textura da moeda de esmeralda
        │       ├── copper_coin.png              # Textura da moeda de cobre
        │       └── ...                          # Texturas das outras moedas
        ├── items/
        │   └── custom_coins.json                # Definir itens customizados (moedas)
        └── manifest.json