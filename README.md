#  FallTrack — Análise de Trajetória de Queda

> ** Em construção** — Este repositório está em desenvolvimento ativo. O código será adicionado progressivamente conforme o projeto avança.

---

## Sobre o projeto

**FallTrack** é um aplicativo mobile desenvolvido para analisar vídeos de objetos em queda livre e calcular sua trajetória com base nos frames extraídos. O app processa o vídeo, detecta o objeto em cada frame e aplica cálculos físicos para determinar posição, velocidade e aceleração ao longo do tempo, exibindo os resultados em gráficos e relatórios interativos.

---

## Funcionalidades previstas

- Gravação ou importação de vídeo pelo celular
- Configuração de FPS, recorte e seleção de objeto
- Envio do vídeo para processamento no servidor
- Detecção automática do objeto por frame 
- Cálculo de trajetória, velocidade e aceleração
- Gráfico animado da rota de queda
- Tabela de dados frame a frame
- Vídeo original com overlay da trajetória
- Exportação de relatório em PDF
- Histórico de análises salvas localmente

---

## Stack tecnológica

### App mobile
| Tecnologia | Função |
|---|---|
| React Native (Expo) | Interface mobile iOS e Android |
| Victory Native | Gráficos de trajetória |
| React Native Skia | Renderização 2D da rota |

### Servidor
| Tecnologia | Função |
|---|---|
| Python + FastAPI | API REST para processamento |
| OpenCV | Extração de frames e detecção de objeto |
| NumPy / SciPy | Cálculos físicos e ajuste de curva |
| YOLOv8 (opcional) | Detecção automática de objetos |

---

## Estrutura do repositório

```
falltrack/
├── app/                  
│   ├── src/
│   │   ├── screens/      
│   │   ├── components/   
│   │   └── services/     
│   └── package.json
│
├── server/             
│   ├── main.py          
│   ├── processing/       
│   └── requirements.txt
│
└── README.md
```

---

## Status do projeto

| Etapa | Status |
|---|---|
| Definição da arquitetura | ✅ Concluído |
| Estrutura do repositório |  ✅ Concluído |
| Backend — processamento de vídeo |  Pendente |
| App mobile — telas principais |  Pendente |
| Integração app ↔ servidor |  Pendente |
| Telas de resultado e gráficos |  Pendente |
| Exportação de relatório PDF |  Pendente |
| Testes e ajustes finais |  Pendente |

---

## Como contribuir

O projeto está em fase inicial. Em breve serão adicionadas instruções de instalação, configuração do ambiente e guia de contribuição.

---

