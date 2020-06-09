# exposure-fusion
Trabalho de Computação Gráfica e Multimídia acerca da técnica Exposure Fusion

## Executando o código

O código foi desenvolvido em Python e utilizamos o Jupyter Notebook para execução. Ele tem como objetivo criar uma imagem final melhorada a partir de  uma sequência de imagens capturadas com tempos de exposição diferentes, através da técnica exposure fusion.

Caso queira testar em sua máquina, siga os seguintes passos:

- Clone este repositório;
- Através do Jupyter Notebook, abra o arquivo **exposure_fusion_run.ipynb**;
- Certifique-se de que as bibliotecas utilizadas estejam instaladas em seu computador; caso não estejam, faça as instalações;
```bash
$ pip install os-sys
$ pip install opencv-python
$ pip install numpy
$ pip install matplotlib
```
- A única **modificação necessária** a ser feita é na linha destacada abaixo, na qual você deverá preencher com o caminho, em seu computador, até a pasta com as imagens que deseja realizar a fusão;
```python
path = r"C:\Users\emanu\Desktop\Projects\exposure-fusion\room"
```
- Outra possível modificação, mas não necessária, está compreendidada nesta próxima linha, onde você pode alterar o nome da imagem final a ser salva para que não sobrescreva as anteriores;
```python
cv2.imwrite('img_MultiresolutionFusion2.png', final_imageD.astype('uint8'))
```
- Feito os passos anteriores, basta rodar a aplicação. As imagens resultantes ficarão salvas na pasta **results**.

## Resultados

As imagens abaixo mostram os resultados obtidos ao utilizar o algoritmo proposto:

### Coleção de imagens
![](images_doc/room_before.png)
### Imagem final
![](images_doc/room_after.png)

### Coleção de imagens
![](images_doc/street_before.png)
### Imagem final
![](images_doc/street_after.png)

### Coleção de imagens
![](images_doc/taipei_before.png)
### Imagem final
![](images_doc/taipei_after.png)
