# 📐 Calculadora Geométrica em Java

Este projeto é uma aplicação simples em **Java**, feita para praticar e demonstrar conceitos de **Programação Orientada a Objetos (POO)**, como:

- Abstração  
- Herança  
- Polimorfismo  
- Sobrescrita de métodos  
- Organização de classes por responsabilidade  

A aplicação permite calcular **área** e **perímetro** de diferentes figuras geométricas, usando entrada de dados pelo console.

---

## 🚀 Funcionalidades

A calculadora atualmente permite trabalhar com as seguintes figuras:

### ➤ **Círculo**
- Área  
- Perímetro  

### ➤ **Retângulo**
- Área  
- Perímetro  

### ➤ **Quadrado**
- Área  
- Perímetro  

### ➤ **Triângulo**
- Área  
- Perímetro  

O usuário informa os valores necessários (base, altura, lados, raio etc.) e o programa retorna os resultados formatados no terminal.

---

## 🧠 Conceitos utilizados

### ✔ **Classe abstrata**
Uma classe `Calcular` define a estrutura base para todos os cálculos.

### ✔ **Herança**
Cada figura geométrica herda a classe abstrata e implementa seus próprios cálculos.

### ✔ **Polimorfismo**
Cada figura sobrescreve os métodos:
```java
public void calcularArea();
public void calcularPerimetro();
✔ Encapsulamento
Uso de getters/setters para acessar resultados.

✔ Menu interativo
Permite ao usuário escolher qual figura deseja calcular.

📁 Estrutura do projeto
src/
 └── br/com/fiap/calculargeometria/
     ├── model/
     │    ├── Calcular.java
     │    ├── Circulo.java
     │    ├── Quadrado.java
     │    ├── Retângulo.java
     │    └── Triangulo.java
     │
     └── app/
          └── App.java

```

## 📜 Licença
Este projeto é livre para estudo e modificação.
