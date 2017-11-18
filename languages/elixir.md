# Elixir

A dynamic, functional language for building scalable and maintainable applications. Elixir runs on the Erlang VM so is popular with low-latency, distributed and fault-tolerant systems.

## Level 1

* Complete the [Elixir Koans](https://github.com/elixirkoans/elixir-koans)
* Read [Programming Elixir](https://pragprog.com/book/elixir/programming-elixir)
* Use [Mix](https://hexdocs.pm/mix/Mix.html) to create Elixir project structures
* Use [ExUnit](https://hexdocs.pm/ex_unit/ExUnit.html) to TDD out solutions.
* Solve some katas in Elixir such as Roman Numerals

### You should be able to

* Use `iex` to try things out in the repl.
* Define and invoke functions.
* Use the pipe operator.
* Destructure data structures like lists and maps.
* Use pattern matching.
* Use [Mix](https://hexdocs.pm/mix/Mix.html) to create and run projects.
* Use [ExUnit](https://hexdocs.pm/ex_unit/ExUnit.html) to run tests.
* Use `iex` to invoke your programs.
* Solve small problems with Elixir.

## Level 2

* Write a Tic-Tac-Toe game in Elixir.
* Contribute to an open-source Elixir project like adding a koan [Koans](https://hexdocs.pm/mix/Mix.html).
* Write a mix task that can be used to invoke the Tic-Tac-Toe game.

### You should be able to

* Write entire programs in Elixir.
* Understand how to trouble shoot problems and use the Elixir documentation.
* Understand how to write Mix tasks.

## Level 3

* Write a small web api using [Plug](https://hexdocs.pm/plug/readme.html) that returns the current date and time when the endpoint is hit.
* Write a small web application such as web based Roman Numerals using [Phoenix](http://phoenixframework.org/)
* Write a Phoenix web Tic-Tac-Toe application.
* Read [Progamming Phoenix](https://pragprog.com/book/phoenix/programming-phoenix)

### You should be able to

* Understand how to write web applications in Phoenix.

## Level 4

* Write an application which calculates the fibanacci series using a GenServer or Agent for in memory storage of previously calculated results.
* Write a To-Do application which uses a database for persistance, which saves the state of each 'to-do' using [Ecto](https://hexdocs.pm/ecto/Ecto.html) and Postgres.

### You should be able to

* Understand the GenServer and Agent callbacks.
* Understand how to start OTP processes such as Ecto.
* Understand how to configure Postgres and use Ecto.
* Understand different configurations for testing with the Ecto Sandbox.

## Level 5

* Use an Umbrella project to create a project in Elixir that queries several external API's (Twitter, Wikipedia) and displays the results to the user.
* Update the project to run in a distributed fashion.
* Write tests that substitute fake implementations rather than hit the external API's.
* Read [The Little Elixir & OTP Guidebook](https://www.manning.com/books/the-little-elixir-and-otp-guidebook)

### You should be able to

* Understand how to parse XML/JSON.
* Understand how to authenticate yourself with external API's if appropriate.
* Understand the Elixir Umbrella project structure.
* Understand how to switch in real and fake implementations via config to decouple tests from external systems.
* Understand how to start multiple `iex` sessions and connect them in distrubuted mode.
* Understand how distributed systems communicate (e.g: HTTP, rpc)
* Understand how to start different projects from the Umbrella in different `iex` sessions and have them communicate.
