# [Catalog of Elixir-specific code smells][Elixir Smells]

## Table of Contents

* __[About](#about)__
* __[Design-related smells](#design-related-smells)__
  * [GenServer Envy](#genserver-envy)
  * [Agent Obsession](#agent-obsession)
  * [Unsupervised process](#unsupervised-process)
  * [Large messages between processes](#large-messages-between-processes)
  * [Complex multi-clause function](#complex-multi-clause-function)
  * [Complex API error handling](#complex-api-error-handling)
  * [Exceptions for control-flow](#exceptions-for-control-flow)
  * [Untested polymorphic behavior](#untested-polymorphic-behavior)
  * [Code organization by process](#code-organization-by-process)
  * [Data manipulation by migration](#data-manipulation-by-migration)
* __[Low-level concerns smells](#low-level-concerns-smells)__
  * [Working with invalid data](#working-with-invalid-data)
  * [Map/struct dynamic access](#mapstruct-dynamic-access)
  * [Unplanned value extraction](#unplanned-value-extraction)
  * [Modules with identical names](#modules-with-identical-names)
  * [Unnecessary macro](#unnecessary-macro)
  * [App configuration for code libs](#app-configuration-for-code-libs)
  * [Compile-time app configuration](#compile-time-app-configuration)
  * [Dependency with "use" when an "import" is enough](#dependency-with-use-when-an-import-is-enough)

## About

This is the first catalog of code smells specific for the [Elixir programming language][Elixir]. Originally created by Lucas Vegi and Marco Tulio Valente ([ASERG/DCC/UFMG][ASERG]), this catalog consists of 18 Elixir-specific smells.

To better organize the kinds of impacts caused by these smells, we classify them into two different groups: __design-related smells__ <sup>[link](#design-related-smells)</sup> and __low-level concerns smells__ <sup>[link](#low-level-concerns-smells)</sup>.


Please feel free to make pull requests and suggestions.

## Design-related smells

Design-related smells are more complex, affect a coarse-grained code element, and are therefore harder to detect. Next, all 10 different smells classified as design-related are explained and exemplified:

### GenServer Envy

TODO...

[▲ back to Index](#table-of-contents)

### Agent Obsession

TODO...

[▲ back to Index](#table-of-contents)

### Unsupervised process

TODO...

[▲ back to Index](#table-of-contents)

### Large messages between processes

TODO...

[▲ back to Index](#table-of-contents)

### Complex multi-clause function

TODO...

[▲ back to Index](#table-of-contents)

### Complex API error handling

TODO...

[▲ back to Index](#table-of-contents)

### Exceptions for control-flow

TODO...

[▲ back to Index](#table-of-contents)

### Untested polymorphic behavior

TODO...

[▲ back to Index](#table-of-contents)

### Code organization by process

TODO...

[▲ back to Index](#table-of-contents)

### Data manipulation by migration

TODO...

[▲ back to Index](#table-of-contents)


## Low-level concerns smells

Low-level concerns smells are more simple than design-related smells and affect a small part of the code. Next, all 8 different smells classified as low-level concerns are explained and exemplified:

### Working with invalid data

TODO...

[▲ back to Index](#table-of-contents)

### Map/struct dynamic access

TODO...

[▲ back to Index](#table-of-contents)

### Unplanned value extraction

TODO...

[▲ back to Index](#table-of-contents)

### Modules with identical names

TODO...

[▲ back to Index](#table-of-contents)

### Unnecessary macro

TODO...

[▲ back to Index](#table-of-contents)

### App configuration for code libs

TODO...

[▲ back to Index](#table-of-contents)

### Compile-time app configuration

TODO...

[▲ back to Index](#table-of-contents)

### Dependency with "use" when an "import" is enough

TODO...

[▲ back to Index](#table-of-contents)


<!-- Links -->
[Elixir Smells]: https://github.com/lucasvegi/Elixir-Code-Smells
[Elixir]: http://elixir-lang.org
[ASERG]: http://aserg.labsoft.dcc.ufmg.br/