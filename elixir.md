<img href="http://ninjadolinux.com.br/wp-content/uploads/2020/06/1889312_18ff.jpg" />
# elixir
Comando elixir
<hr>

* verifique se o Erlang está ativo.
erl -version
Erlang (SMP,ASYNC_THREADS,HIPE) (BEAM) emulator version 9.3

* elixir --version

mix - h

iex


<hr>
<h3>Build tool</h3>
Elixir vem com uma ferramenta chamada Mix, que é o que eles chamam de “build tool”.<bold><strong> <a href="https://elixir-lang.org/getting-started/mix-otp/introduction-to-mix.html" target="_blank">Mix</a></strong></bold> é responsável por tarefas como criar projetos, executar testes, rodar projetos, rodar tasks, etc. Me parece bastante interessante que uma linguagem nova tenha algo como este, pois demonstra facilidade para que iniciemos ou conhecemos a linguagem, além de demonstrar maturidade por parte de seus desenvolvedores e mantenedores. Além disso a linguagem não me limita a trabalhar com uma IDE ou ambiente específico para que eu possa criar meus projetos, rodar meus testes, etc. Utilizando o Mix eu consigo trabalhar na linha de comando em qualquer ambiente. Fazendo um paralelo, o Mix está para o Elixir assim como o dotnet ou dnx estão (ou deveriam estar) para o .NET (com a diferença, claro, que o Mix parece mais maduro).
<hr>
<h3>Gerenciador de pacotes</h3>
Toda linguagem moderna que se preze necessita de um gerenciador de pacotes. É impensável trabalhar com alguma tecnologia e ter que manualmente baixar pacotes e instalar dependências. Isso é coisa da década passada. E o Elixir também me surpreendeu quanto a isso. <bold><strong> <a href="https://hex.pm/" target="_blank">Hex</a></bold></strong> , seu gerenciador de pacotes, além de ter um logo incrível (que remete ao pluralismo e inclusão) parece estar bastante maduro e em pleno funcionamento.
Pelo que eu pude compreender, Hex é um package manager para a VM do Erlang, com pleno suporte para Mix e Elixir, tendo surgido em 2014. Isso quer dizer que você pode usar Hex para trabalhar tanto com Erlang quanto com Elixir.
