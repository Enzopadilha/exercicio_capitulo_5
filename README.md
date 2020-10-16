# exercicio_capitulo_5
1. Why do we first resize to a large size on the CPU, and then to a smaller size on the GPU?
- Primeiramente aumentamos a imagem o suficiente para que ela tenha margens livres para transformações de aumento sem criar zonas vazias. E usamos uma imagem pequena porque o essa transformação de aumento pede que ela seja reduzida para transformar as imagens em um único tamanho para melhorar o processamento na GPU.

2. If you are not familiar with regular expressions, find a regular expression tutorial and some problem sets, and complete them. Have a look on the book’s website
for suggestions.


3. What are the two ways in which data is most commonly provided for most deep learning datasets?
- Arquivos individuais representando itens de dados, como um documento de texto ou imagens em pastas, e por uma tabela de dados, por exemplo no formato CSV.

4. Look up the documentation for L and try using a few of the new methods that it adds.

5. Look up the documentation for the Python pathlib module and try using a few methods of the Path class.

6. Give two examples of ways that image transformations can degrade the quality of the data.
- Ampliando a imagem, interpolando, girando para direita ou esquerda, interpolando novamente.

7. What method does fastai provide to view the data in a DataLoaders?

8. What method does fastai provide to help you debug a DataBlock?
- O commando 'summary'.

9. Should you hold off on training a model until you have thoroughly cleaned your data?

10. What are the two pieces that are combined into cross-entropy loss in PyTorch?
- Quando pegamos o softmax e depois o log likelihood, a combinação deles é a cross-entropy loss. No Pytorch está disponível como 'nn.CrossEntropyLoss.

11. What are the two properties of activations that softmax ensures? Why is this important?
- Garante que as ativações estão entre 0 e 1 e que a sua soma é igual a 1.

12. When might you want your activations to not have these two properties?

13. Calculate the exp and softmax columns of Figure 5-3 yourself (i.e., in a spreadsheet, with a calculator, or in a notebook).

14. Why can’t we use torch.where to create a loss function for datasets where our label can have more than two categories?

15. What is the value of log(–2)? Why?

16. What are two good rules of thumb for picking a learning rate from the learning rate finder?

17. What two steps does the fine_tune method do?

18. In Jupyter Notebook, how do you get the source code for a method or function?

19. What are discriminative learning rates?

20. How is a Python slice object interpreted when passed as a learning rate to fastai?
