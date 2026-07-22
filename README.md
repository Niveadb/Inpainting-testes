# Inpainting-testes
Repositório de aprendizado sobre inpainting com python para a matéria de computação gráfica na faculdade.

Este projeto usa OpenCV para fazer inpainting em uma imagem com base em uma máscara.

## Como usar

1. Coloque as imagens na mesma pasta que o script:
   - `campo.jpeg`
   - `campo_mask.jpg`

2. Execute o script:
   ```powershell
   python inpainting_cg.py
   ```

3. O script irá:
   - ler a imagem e a máscara
   - aplicar inpainting com métodos diferentes
   - mostrar todas as imagens em um único gráfico
   - salvar os resultados individuais em uma pasta `result_images_campo`

## Observações

- Se o caminho da imagem ou máscara estiver errado, o script exibirá um erro.
- Use Python 3 e tenha OpenCV instalado.
