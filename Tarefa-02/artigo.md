# Linguagem Ruby
Nomes: Fábio França, Rebeca Santos  
**História:**  
A linguagem Ruby foi concebida em 24 de fevereiro de 1993 por Yukihiro Matsumoto, que pretendia criar uma nova linguagem que balanceava programação funcional com a programação imperativa. Matsumoto afirmou: "Eu queria uma linguagem de script que fosse mais poderosa do que Perl, e mais orientada a objetos do que Python. É por isso que eu decidi desenvolver minha própria linguagem.". 
Após o lançamento do Ruby 1.3 em 1999, iniciou-se a primeira lista de discussão em inglês chamada Ruby-Talk, marcando um interesse crescente na linguagem fora do Japão. Em setembro de 2000, o primeiro livro em inglês, Programming Ruby, foi impresso, sendo mais tarde liberado gratuitamente para o público, ajudando no processo de adoção de Ruby por falantes do inglês. 
Por volta de 2005, o interesse pela linguagem Ruby subiu em conjunto com o Ruby on Rails, um framework de aplicações web popular escrito em Ruby. Rails é frequentemente creditada como a aplicação que tornou Ruby "famosa" e a associação é tão forte que ambos são muitas vezes confundidos por programadores que são novos a Ruby. 

Ruby se tornou reconhecida no meio especializado desde que Dave Thomas, conhecido como um dos "Programadores Pragmáticos", adotou-o como uma de suas linguagens preferidas e acabou por escrever um dos mais completos livros sobre a linguagem, o Programming Ruby. Com o advento desta publicação, a linguagem passou a contar com uma boa fonte de iniciação e referência em inglês, aumentando consequentemente o número de adeptos da linguagem no Ocidente.

Ultimamente, devido a grande exposição de um framework web feito em Ruby, o Ruby on Rails desenvolvido por David Heinemeier Hansson, a linguagem tem sido foco da mídia especializada justamente pela sua praticidade.

Esta mesma praticidade inclusive é um dos conceitos básicos desta linguagem. É possível fazer algoritmos que resolvam seus problemas, não necessitando se preocupar com as limitações da linguagem ou do interpretador.  
**Características:**  
Para manter a praticidade, a linguagem possui algumas características interessantes:  


•	A sintaxe é enxuta, quase não havendo necessidade de colchetes e outros caracteres.  
•	Todas as variáveis são objetos, onde até os "tipos primitivos" (tais como inteiro, real, entre outros) são classes.  
•	Estão disponíveis diversos métodos de geração de código em tempo real, como os "attribute accessors".  
•	Através do Ruby Gems, é possível instalar e atualizar bibliotecas com uma linha de comando, de maneira similar ao APT do Debian Linux.  
•	Code blocks (blocos de código), ajudam o programador a passar um trecho de instruções para um método. A idéia é semelhante aos "callbacks" do Java, mas de uma forma extremamente simples e bem implementada.  
•	Mixins, uma forma de emular a herança múltipla, sem cair nos seus problemas.  
•	Tipagem dinâmica, mas forte. Isso significa que todas as variáveis devem ter um tipo (fazer parte de uma classe), mas a classe pode ser alterada dinamicamente. Os "atalhos" citados acima, por exemplo, se beneficiam da tipagem dinâmica para criar os métodos de acesso/alteração das propriedades.  


Ruby está disponível para diversas plataformas, como Microsoft Windows, .NET, Linux, Solaris e Mac OS X, além de também ser executável em cima da máquina virtual do Java (através do JRuby).
Expressividade:
Blocos, uma Característica Verdadeiramente Expressiva
Os blocos do Ruby são vistos como uma fonte de grande flexibilidade. Um programador pode adicionar uma closure a qualquer método, descrevendo como esse método deve se comportar. A closure é chamada de bloco e tornou-se uma das características mais populares para os recém chegados ao Ruby vindos de outras linguagens imperativas como o PHP ou o Visual Basic.
Os blocos são inspirados nas linguagens funcionais. Matz disse, “nas closuresem Ruby, eu quis respeitar a cultura do Lisp”.  

Exemplo:
search_engines =
  %w[Google Yahoo MSN].map do |engine|
    "http://www." + engine.downcase + ".com"
  end
