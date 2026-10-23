# Garagem (cliente)

Ponto de partida do workshop: uma tela com o carro já desenhado. Todo o resto é construído por você, seguindo as instruções do workshop e a documentação.

```bash
cd client-garage/src
python3 -m http.server 8080      # http://localhost:8080 (também funciona abrindo index.html direto)
```

## Arquivos

- `src/index.html`, `src/app.js`: a tela, que só desenha o carro
- `src/car-renderer.js`: módulo pronto de desenho do carro
- `src/style.css`

## Documentação

- Contrato do carro: [`docs/car-contract.md`](docs/car-contract.md)
- Módulo de desenho: [`docs/car-renderer.md`](docs/car-renderer.md)
- API: [`docs/api.md`](docs/api.md)
