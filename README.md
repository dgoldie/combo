Combo
=====

**A first Elixir project**

Needs some tests.

## How to start:

    2.1.2 apollo:~/code/work/erlangSV
    $ mix new combo
    * creating README.md
    * creating .gitignore
    * creating mix.exs
    * creating config
    * creating config/config.exs
    * creating lib
    * creating lib/combo.ex
    * creating test
    * creating test/test_helper.exs
    * creating test/combo_test.exs

    Your mix project was created successfully.
    You can use mix to compile it, test it, and more:

        cd combo
        mix test

    Run `mix help` for more commands.

    2.1.2 apollo:~/code/work/erlangSV
    $ cd combo
    2.1.2 apollo:~/code/work/erlangSV/combo
    $ ls
    README.md  config/    lib/       mix.exs    test/

**Add files as shown, then compile**

    2.1.2 apollo:~/code/work/erlangSV/combo
    $ mvim .
    2.1.2 apollo:~/code/work/erlangSV/combo
    $ mix compile
    Compiled lib/sub.ex
    Compiled lib/add.ex
    Compiled lib/combo.ex
    Generated combo.app
    2.1.2 apollo:~/code/work/erlangSV/combo
    $ iex -S mix
    Erlang/OTP 17 [erts-6.0] [source] [64-bit] [smp:8:8] [async-threads:10] [hipe] [kernel-poll:false] [dtrace]

    Interactive Elixir (1.0.2) - press Ctrl+C to exit (type h() ENTER for help)
    iex(1)> Combo.add(5,2)
    7
    iex(2)> Add.add(3,2)
    5
    iex(3)> 
