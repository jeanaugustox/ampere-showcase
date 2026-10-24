# Carrossel de telas do AMPERE

Página estática preparada para apresentar as jornadas do AMPERE e ser incorporada ao Google Sites.

## Conteúdo

- 19 telas reais do sistema;
- filtros para Acesso, Projetista, Analista e Normas;
- navegação por botões, indicadores e teclado;
- ampliação das capturas;
- layout responsivo.

## Visualização local

Na pasta deste projeto, execute:

```powershell
python -m http.server 4173 --directory dist
```

Depois acesse `http://localhost:4173`.

## Uso no Google Sites

O Google Sites não publica uma pasta HTML local. Primeiro hospede o conteúdo da pasta `dist` em um endereço HTTPS, como GitHub Pages, Cloudflare Pages ou outro serviço estático.

Depois, no editor do Google Sites:

1. Escolha **Inserir**.
2. Clique em **Incorporar**.
3. Selecione **Por URL**.
4. Cole o endereço HTTPS da página hospedada.
5. Clique em **Inserir** e ajuste a altura do bloco.

Mantenha `index.html` e a pasta `assets` juntos na hospedagem.
