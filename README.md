# Classificação-de-textos
## Projeto desenvolvido por:
- [Júlia Campos](https://github.com/juliacamposn)

## Descrição
- Este é um projeto da disciplina de Inteligência Artificial, que tem como objetivo classificar textos usando de qualquer arquitetura para classificação de textos disponível no site [Hugging face](https://huggingface.co/models?pipeline_tag=text-classification&sort=trending). No mais, deveriamos escolher duas arquiteturas distintas e posteriormente escolher uma para fazer deploy no telegram.
- As duas arquiteturas que eu escolhi foram [SamLowe/roberta-base-go_emotions](https://huggingface.co/SamLowe/roberta-base-go_emotions) que classifica sentimentos em positivo, negativo e neutro, e [facebook/fasttext-language-identification](https://huggingface.co/facebook/fasttext-language-identification) que entre outras coisas, faz classificação de texto para qual idioma está o texto, calcula a similaridade das palavras em diferentes idiomas, isso tudo graças ao modelo ter sido treinado em 157 idiomas diferentes.

## Desenvolvimento
- O projeto foi desenvolvido usando o Google Colab.
- Como eram arquiteturas bem distintas usei dois arquivos .pynb um para cada modelo. No arquivo trabalho_2_classifcação-de-texto.ipynb encontra-se o modelo 1 roberta-base-go_emotions, e no arquivo m2-t2-ia.ipynb encontra-se o modelo 2 fasttext-language-identification.
- O modelo que foi escolhi para fazer deploy no telegram foi trabalho_2_classifcação-de-texto.ipynb(roberta-base-go_emotions) que faz classificação de emoções entre positivo, negativo e neutro.
