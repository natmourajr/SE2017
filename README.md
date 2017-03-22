# SE2017
Repositório para o mini-curso da Semana de Eletrônica 2017

## Conteúdo previsto

Aprendizado de Máquina + Python

### Temas abordados
	Redes Neurais Supervisionadas
	Deep Learning
	Redes não-supervisionadas

### Para rodar os exemplos
No Ubuntu
```
>> sudo apt-get install python-pip
```
No MacOS
```
>> sudo easy_install pip
```
Com o pip instalado

```
>> sudo pip install virtualenv
>> mkdir ~/.virtualenvs
>> cd ~/.virtualenvs
>> virtualenv se2017
>> source ~/.virtualenvs/se2017/bin/activate
```
Para atualizar o pip (recomendo fortemente)
```
>> pip install --upgrade pip
```
Com o pip instalado e atualizado, clone o repositório do GitHub
```
>> cd <Diretório de Trabalho>
>> git clone https://github.com/natmourajr/SE2017.git
>> cd SE2017
```
Faça a instalação das bibliotecas necessárias
```
>> pip install -r requirements.txt
```
Para rodar:
```
>> cd examples
>> jupyter notebook
```
Em caso de erro nas redes neurais
```
>> vim $HOME/.keras/keras.json 
```
Mudar "backend": "theano"
