# Phoenix_AJAX

A resource generator for Phoenix which provides templates with AJAX functionality
utilizing the Semantic UI framework functionality.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add phoenix_ajax to your list of dependencies in `mix.exs`:

        def deps do
          [{:phoenix_ajax, "~> 0.0.1"}]
        end

  2. Ensure phoenix_ajax is started before your application:

        def application do
          [applications: [:phoenix_ajax]]
        end

## Generators

### Generate Resource

Generates a Phoenix resource similar to ```mix phoenix.gen.html``` with
AJAX functionality.

```
mix phoenix_ajax.gen.html User users name:string age:integer
```
