# React Google Maps Web Marker Rotation

## Descrição

Este projeto demonstra como rotacionar marcadores personalizados (markers) no Google Maps usando React. Ideal para aplicações que exibem veículos, objetos ou direções dinâmicas, como aplicativos de transporte, logística, rastreamento e navegação.

## Tecnologias Utilizadas

- **React** (Vite)
- **@react-google-maps/api** (ou similar)
- **Google Maps JavaScript API**
- **Geolocation API** (opcional)
- **Custom marker icons** em SVG/PNG para rotação

## Funcionalidades

- Exibe o mapa do Google Maps integrado ao React
- Adiciona marcadores com ícones customizados
- Permite rotacionar marcadores dinamicamente (ex: indicando direção de movimento)
- Atualização da rotação via props ou eventos
- Suporte a múltiplos marcadores e ângulos
- Configuração fácil da chave de API via `.env`

## Como usar

1. **Clone o repositório:**
    ```bash
    git clone https://github.com/fabiocberg/react-google-maps-web-marker-rotation.git
    cd react-google-maps-web-marker-rotation
    ```

2. **Instale as dependências:**
    ```bash
    npm install
    # ou
    yarn install
    ```

3. **Configure sua chave de API:**
    - Crie um arquivo `.env` na raiz do projeto:
      ```
      VITE_GOOGLE_API_KEY=SUA-CHAVE-API-GOOGLE
      ```
    - Habilite a Maps JavaScript API no seu projeto do Google Cloud.

4. **Rode o projeto:**
    ```bash
    npm run dev
    # ou
    yarn dev
    ```
    O app estará disponível em `http://localhost:5173` (ou porta definida pelo Vite).

## Exemplos de Uso

- Mostrar veículos, bicicletas, drones ou objetos rotacionando conforme direção
- Indicar direção de movimento em tempo real em mapas
- Simulações e tracking

## Estrutura de Pastas

```
src/
├── components/        # Map, RotatingMarker, Controls, etc.
├── hooks/             # Hooks customizados para integração com Google Maps
├── utils/             # Funções auxiliares de rotação, cálculo de ângulo, etc.
├── App.jsx            # Componente principal
└── main.jsx           # Inicialização
```

## Dicas de Personalização

- Utilize SVG para facilitar rotação dinâmica dos ícones
- Receba o ângulo de rotação como prop ou calcule a partir de coordenadas
- Integre com fontes de dados externas para atualizar a rotação automaticamente

## Licença

MIT

---

> Este projeto é um ponto de partida para quem deseja criar mapas interativos com marcadores dinâmicos e rotacionáveis em aplicações React.