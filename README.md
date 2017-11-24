# ESTUDOS TENSORFLOW
Repositório destinado a compartilhar todo conhecimento que conseguir com as minhas pesquisas.

PS: Antes de começar(Instalar o Tensorflow)
//MAIS INFROMAÇÕES EM https://www.tensorflow.org/install/
Comoe eu fiz:
No terminal do Ubuntu
//Baixar pip
//Usar esse comando para python 2.7
 sudo apt-get install python-pip python-dev
 //Usar esse comando para python 3
 sudo apt-get install python3-pip python3-dev 
 
 //Instalar o tensorflow via pip
  //Para python 2.7
  pip install tensorflow
  //Para python 3
  pip3 install tensorflow

//DENTRO DO PYTHON, TESTAR O TENSORFLOW
//PARA ENTRAR NO PYTHON, DIGITE PYTHON NO TERMINAL DO UBUNTU
import tensorflow as tf
hello = tf.constant('Hello, TensorFlow!')
sess = tf.Session()
print(sess.run(hello))

//Se exibir Hello, TensorFlow, foi instalado corretamente!
