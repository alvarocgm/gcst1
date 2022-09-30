![Deploy badge](https://github.com/alvarocgm/gcst1/actions/workflows/codeql.yml/badge.svg)
![Deploy badge](https://github.com/alvarocgm/gcst1/actions/workflows/maven.yml/badge.svg)

# Trabalho 1 Gerenciamento e Configuração de Software
Alunos: Álvaro Machado e Pedro Soares

Problema: https://www.beecrowd.com.br/judge/en/problems/view/1099

Sum of Consecutive Odd Numbers II


Read an integer N that is the number of test cases. Each test case is a line containing two integer numbers X and Y. Print the sum of all odd values between them, not including X and Y.

Input
The first line of input is an integer N that is the number of test cases that follow. Each test case is a line containing two integer X and Y.

Output
Print the sum of all odd numbers between X and Y.

<p>Input Sample	
<p>7
<p>4 5
<p>13 10
<p>6 4
<p>3 3
<p>3 5
<p>3 4
<p>3 8
<p>Output Sample
<p>0
<p>11
<p>5
<p>0
<p>0
<p>0
<p>12
  
Para clonar o repositório com os testes e fazendo o programa rodar automaticamente:
<p>git clone -b bee --single-branch https://github.com/alvarocgm/gcst1.git
 <p> e os seguintes comandos:
   <p>// muda para o diretorio criado
  <p>cd gcst1
 
// faz os testes também
<p>mvn package
  
// roda o programa
<p>java -cp target\GCSTrab1Bee-1.0-BeeCrowd.jar T1.MainApp
