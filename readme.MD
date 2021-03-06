# CudaMatrix

Um simples código feito por um simples estudante de Ciência da Computação para utilizar os núcleos CUDA para operações matriciais. Ignore erros, vazamentos de memória e operações não otimizadas, ainda estou aprendendo. e.e


## Instruções:

|  GPU? | Instrução | Detalhes | Exemplo | Local de execução |
|-------|-----------|----------|---------|-------------------|
| :heavy_check_mark: | add() | Adição de duas matrizes de tamanhos iguais | c = a+b | GPU |
| :heavy_check_mark: | addScalar() | Adição de um valor estático na matriz | c = a+x | GPU |
| :heavy_check_mark: | clip() | Limita o máximo e o mínimo de um valor na matriz | max < a > min | GPU |
| :heavy_check_mark: | divideScalar() | Divide a matriz por um valor estático | c = a/x | GPU |
| :heavy_check_mark: | exp() | Constante de Euler elevado ao valor da matriz | c = e^a | GPU |
| :heavy_check_mark: | logit() | Aplica a função logit na matriz | Derivada da sigmoid | GPU |
| :heavy_check_mark: | multiply() | Multiplica 2 matrizes | C = A\*B | GPU |
| :heavy_check_mark: | multiplyHadamard() | Multiplica 2 matrizes com a regra de hadamard | c = a\*b | GPU |
| :heavy_check_mark: | multiplyScalar() | Multiplica a matriz por um valor estático | c = a\*x | GPU |
| :heavy_multiplication_x: | randomFill() | Preenche a matriz com valores aleatórios | c = rand(0~1) | CPU |
| :heavy_multiplication_x: | randomFillSmall() | Preenche a matriz com valores aleatórios pequenos | c = rand(0~0.01) | CPU |
| :heavy_check_mark: | sigmoid() | Aplica a função sigmoid na matriz | c = 1 / (1+e^-a) | GPU |
| :heavy_check_mark: | softmax() | Aplica a função softmax na matriz | c = exp(a) / (sum(exp(a))) | GPU |
| :heavy_check_mark: | subtraction() | Subtrai 2 matrizes | c = a-b | GPU |
| :heavy_check_mark: | subtractScalar() | Subtrai os valores de uma matriz por uma constante | c = a-x | GPU |
| :heavy_check_mark: | subtractScalarInverse() | Subtrai inversamente os valores de uma matriz por uma constante | c = x-a | GPU |
| :heavy_multiplication_x: | sumAll() | Soma todos os valores de uma matriz | sum(a) | CPU |
| :heavy_check_mark: | tanh() | Aplica a função tanh na matriz | C = tanh(A) | GPU |
| :heavy_check_mark: | transpose() | Faz a transposição da matriz | C(i,j) = A(j,i) | GPU |

# Copyright

Copyright 2020, Lucas Scarpinelli Tomazetto, CudaMatrix

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

