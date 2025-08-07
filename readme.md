# Neuron Without Libraries

## English

This project is an experimental exercise I carried out during the August holidays for my own entertainment. It implements a single artificial neuron using only the **numpy** and **matplotlib** libraries, without relying on frameworks such as TensorFlow or PyTorch.  
It is written in the Menorquí dialect of Catalan because it is the language I think in, and this project really was solely for my entertainment, not for publication.

### Technical Overview

- **Neuron Architecture:**  
  The neuron is implemented as a Python class with a weight vector and bias. The neuron computes its output by applying a linear combination of inputs followed by an activation function. Available activation functions include sigmoid, tanh, and ReLU (defined via lambda functions in a configuration cell).

- **Training Method:**  
  Training is performed using gradient descent. For each data point:
  - The output is computed using the chosen activation function.
  - The error is determined by subtracting the neuron's output from the expected target.
  - The error is squared (to ensure a non-negative value and to penalize larger errors) and accumulated.
  - The weights and bias are updated based on the gradient of the error derived from the activation function.
  
- **Datasets:**  
  Two datasets are used; both are created by GPT-o4-mini—just like this README—and reviewed and supervised by me.
  - **XOR Dataset:** Demonstrates the inability of a single neuron to fully classify non-linearly separable data.
  - **Vertebrate vs Invertebrate Dataset:** A linear classification task that achieves better performance.

- **Project Roadmap:**  
  In a future project, I plan to extend this work to build a complete neural network by combining multiple neurons into hidden layers, enabling the model to solve more complex problems.

---

## Català

Aquest projecte és un exercici experimental que he realitzat durant les vacances d'agost per entretenir-me. S'implementa una única neurona artificial utilitzant només les llibreries **numpy** i **matplotlib**, sense recórrer a frameworks com TensorFlow o PyTorch.  
Està escrit en el dialecte del català menorquí, ja que és l'idioma en què penso, i aquest projecte realment era únicament per entretenir-me, no per publicar.

### Descripció tècnica

- **Arquitectura de la neurona:**  
  La neurona s'implementa com una classe Python amb un vector de pesos i un biaix. La neurona calcula la seva sortida aplicant una combinació lineal d'inputs seguida d'una funció d'activació. Es poden utilitzar funcions d'activació com la sigmoid, la tanh o la ReLU (definides com a funcions lambda en un fitxer de configuració).

- **Mètode d'entrenament:**  
  L'entrenament es realitza mitjançant descens de gradient. Per cada dada:
  - Es calcula la sortida utilitzant la funció d'activació escollida.
  - Es calcula l'error com la diferència entre el valor esperat i el resultat obtingut.
  - L'error s'eleva al quadrat (per garantir un valor sempre positiu i penalitzar errors grans) i s'acumula.
  - S'actualitzen els pesos i el biaix en funció del gradient de l'error derivat de la funció d'activació.

- **Datasets:**  
  S'utilitzen dos datasets, creats per gpt-o4-mini, igual que aquest readme, conten amb la meva revisió i supervisió:
  - **Dataset XOR:** Mostra la limitació d'una única neurona per classificar dades no linealment separables.
  - **Dataset Vertebrat vs Invertebrat:** Una tasca de classificació lineal amb millors resultats.

- **Futur del projecte:**  
  Properament desenvoluparé un segon projecte en el qual crearé múltiples neurones per formar una xarxa neuronal completa.

---

## Español

Este proyecto es un ejercicio experimental que he realizado durante las vacaciones de agosto para entretenerme. Se implementa una única neurona artificial utilizando únicamente las librerías **numpy** y **matplotlib**, sin depender de frameworks como TensorFlow o PyTorch.  
Está escrito en el dialecto menorquín del catalán, ya que es el idioma en el que pienso, y este proyecto realmente era únicamente para entretenerme, no para publicar.

### Descripción técnica

- **Arquitectura de la neurona:**  
  La neurona se implementa como una clase en Python con un vector de pesos y un sesgo. La neurona calcula su salida mediante una combinación lineal de entradas seguida de una función de activación. Se pueden utilizar funciones de activación tales como la sigmoide, tanh o ReLU (definidas como funciones lambda en un archivo de configuración).

- **Método de entrenamiento:**  
  El entrenamiento se realiza mediante descenso del gradiente. Para cada muestra:
  - Se calcula la salida utilizando la función de activación elegida.
  - Se determina el error como la diferencia entre la salida obtenida y el valor esperado.
  - El error se eleva al cuadrado (para asegurar un valor no negativo y penalizar errores grandes) y se acumula.
  - Se actualizan los pesos y el sesgo en función del gradiente del error obtenido.
  
- **Datasets:**  
  Se utilizan dos datasets, creados por gpt-o4-mini, igual que este readme, cuentan con mi revisión i supervisión:
  - **Dataset XOR:** Demuestra la incapacidad de una única neurona para clasificar correctamente datos que no son linealmente separables.
  - **Dataset Vertebrado vs Invertebrado:** Una tasca de classificació lineal que obté millors resultats.

- **Futuro del proyecto:**  
  En un futur pròxim desenvoluparé un segon projecte en el qual crearé múltiples neurones per formar una xarxa neuronal completa.