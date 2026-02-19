# Projeto 03 - Perfil de Desenvolvedor (Kotlin) ⚡

**Objetivo**: Praticar a sintaxe concisa do Kotlin e Data Classes.

## O Desafio
1.  Crie uma `data class Dev(val nome: String, val stack: String, val nivel: String)`.
2.  Na Activity, crie uma instância dessa classe.
3.  Use **String Templates** para exibir uma mensagem formatada em um TextView:
    "Olá, meu nome é ${dev.nome}, sou dev ${dev.stack} e meu nível é ${dev.nivel}."
4.  Implemente um botão que, ao ser clicado, altera o nível do dev de "Estagiário" para "Júnior".

## Dica
Use `val` para a instância da classe, mas lembre-se que se precisar mudar uma propriedade interna, a classe original deve permitir ou você deve usar o método `.copy()`.