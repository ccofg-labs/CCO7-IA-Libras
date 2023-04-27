# Detector de Libras

Projeto Desenvolvido na Caderia de Inteligência Artifical do Curso Ciência da Computação, Esse código, faz a interpretação de libras a partir de uma webcam. Atualmente o treinamento contém apenas 10 palavras.

## Contribuidores

<table>
  <tr>
    <td align="center">
        <img src="https://avatars.githubusercontent.com/u/" width="80px;" alt="Diego Leornado"/>
        <br/>
        <sub>
            <b>Diego Leonardo</b>
        </sub>
	</td>
    <td align="center">
		<a href="https://github.com/">
			<img src="https://avatars.githubusercontent.com/u/paulofreitas_py" width="80px;" alt="Paulo Freitas"/>
			<br/>
			<sub>
				<b>Paulo Freitas</b>
			</sub>
		</a>
	</td>
    <td align="center">
		<a href="https://github.com/">
			<img src="" width="80px;" alt="Rodrigo"/>
			<br/>
			<sub>
				<b>Rodrigo </b>
			</sub>
		</a>
	</td>
  </tr>
</table>


## Execução

1. Instale as [dependências](#Dependências).
1. Clone o repositório.
    ```cmd
    git clone https://github.com/ccofg-labs/CCO7-IA-Libras.git
    cd CCO7-IA-Libras
    ```
1. (Opcional) Salve o modelo de treimento na pasta "model".
1. (Opcional) Salve o modelo LabelEncoder com nome "words.encoder.npy".
1. Conecte a WebCam na porta USB do seu computador.
1. Execute o identificador de libras:
    ```cmd
    python .\libras.py
    ```


## Dependências

Esse código foi testado na versão 3.9 do [Python](https://www.python.org/downloads/) e utiliza as seguintes bibliotecas para geração do dataset:

* OpenCV 
    ```cmd
    pip install opencv-python
    ```
* Pandas
    ```cmd
    pip install pandas
    ```
* MediaPipe
    ```cmd
    pip install mediapipe
    ```
* Numpy
    ```cmd
    pip install numpy
    ```
* Scikit-Learn
    ```cmd
    pip install scikit-learn
    ```
* TensorFlow 
    ```cmd
    pip install tensorflow
    ```
* TensorFlow GPU (opcional)
    ```cmd
    pip install tensorflow-gpu
    ```
