# Bagagem Aeroporto

Sistema desenvolvido em Python para simular o processo de compra de franquias de bagagem de uma companhia aérea fictícia, incluindo o cálculo de excesso de peso e a aplicação de taxas adicionais.

## Funcionalidades

* Seleção entre diferentes categorias de bagagem:

  * Econômica
  * Executiva
  * Primeira Classe
* Cálculo automático do valor total da compra
* Verificação de excesso de peso
* Aplicação de taxas adicionais conforme o plano escolhido
* Exibição do peso excedente acumulado
* Processamento de múltiplas bagagens em uma única sessão

## Tecnologias Utilizadas

* Python 3

## Regras de Negócio

| Plano           | Limite de Peso | Valor Base | Taxa por Excesso |
| --------------- | -------------- | ---------- | ---------------- |
| Econômica       | 23 kg          | R$ 80,00   | R$ 130,00        |
| Executiva       | 32 kg          | R$ 120,00  | R$ 160,00        |
| Primeira Classe | 40 kg          | R$ 180,00  | R$ 200,00        |

## Como Executar

1. Clone este repositório:

```bash
git clone URL_DO_REPOSITORIO
```

2. Acesse a pasta do projeto:

```bash
cd bagagem-aeroporto
```

3. Execute o programa:

```bash
python main.py
```

## Exemplo de Uso

```text
Digite seu plano desejado e o peso de sua mala:
economica 28

Plano não compatível com o peso da carga!

Digite seu plano desejado e o peso de sua mala:
fim

Voo finalizado!
Peso total excedido: 5.00kg
Valor total de compra: R$ 210.00
```

## Aprendizados

Este projeto foi desenvolvido com o objetivo de praticar conceitos fundamentais de programação, incluindo:

* Variáveis e constantes
* Estruturas condicionais
* Laços de repetição
* Acumulação de valores
* Validação de entradas
* Regras de negócio
* Manipulação de strings

## Melhorias Futuras

* Refatorar o código utilizando funções
* Utilizar dicionários para armazenar os planos
* Implementar tratamento de exceções
* Salvar histórico de compras em arquivo
* Criar uma interface gráfica
* Adicionar testes automatizados

## Autor

Desenvolvido por Nicollas.
