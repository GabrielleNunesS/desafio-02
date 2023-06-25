# :page_facing_up: Relatório Técnico

### Tecnologias e Ferramentas Utilizadas
* Java
* SpringBoot
* PostMan
* Bibliotecas: Validation, Validator, Lombok

### Desafios e Soluções
* Dificuldade ao tentar rodar cada API em um único endereço @RequestMapping("/eletrodomesticos"). Não sendo possível, foi necessário cria um endereço para cada @RequestMapping().
* Dificuldades na implatanção da validações, devido não compreensão do método privado **validar()**. Após pesquisas e implantação o Validator passou a funcionar como nas aulas.
