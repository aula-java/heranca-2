## [Linguagem de Programação Orientada a Objetos 1](https://rodrigonoll.github.io/java/lpoo-1.html)

### [Exercício: Conceitos Avançados: Herança e Reescrita](https://rodrigonoll.github.io/java/avancado/#/3)

1. Clone o projeto [https://github.com/aula-java/heranca-2](https://rodrigonoll.github.io/java/heranca-2)
2. Crie duas subclasses de Conta chamadas **ContaCorrente** e **ContaPoupanca**.
3. Reescreva o método **deposita** da **ContaCorrente** para descontar além do valor uma taxa de 10 centavos.
4. Reescreva o método **atualiza** da **ContaCorrente** conforme abaixo. Faça as modificações na classe Conta para que não haja erros de compilação.
```
	public void atualiza(double taxa) {
		this.saldo += this.saldo * taxa * 2;
	}
```
5. Reescreva o método **atualiza** da **ContaPoupanca** conforme abaixo. 
```
	public void atualiza(double taxa) {
		this.saldo += this.saldo * taxa * 3;
	}
```
6. Retire os comentários dos testes unitários e crie as asserções nos testes unitários para verificar se o saldo foi atualizado corretamente pelos métodos testados.

