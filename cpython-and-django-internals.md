# CPython and Django Internals

## Python Source

Kenneth Reitz Advice to Me 
* Python Object Model, [Python Data Model Docs](https://docs.python.org/3/reference/datamodel.html)
* Python Magic Classes

Automata
* [Automata-Based Programming Wikipedia](https://en.wikipedia.org/wiki/Automata-based_programming)

The Two Types of Finite Automata
* [Nondeterministic Finite Automaton Wikipedia](https://en.wikipedia.org/wiki/Nondeterministic_finite_automaton)
* [Deterministic Finite Automaton Wikipedia](https://en.wikipedia.org/wiki/Deterministic_finite_automaton)

Trees, Symbol Table, Control Flow Graph
* [Tree Data Structure Wikipedia](https://en.wikipedia.org/wiki/Tree_(data_structure))
* [Parse Tree Wikipedia](https://en.wikipedia.org/wiki/Parse_tree)
* [Syntax Tree Wikipedia](https://en.wikipedia.org/wiki/Syntax_tree )
* [Abstract Syntax Tree Wikipedia](https://en.wikipedia.org/wiki/Abstract_syntax_tree)
* [Symbol Tree Wikipedia](https://en.wikipedia.org/wiki/Symbol_table)
* [Control Flow Graph Wikipedia](https://en.wikipedia.org/wiki/Control-flow_graph)

<!--
Abstract Syntax Trees
https://docs.python.org/3/library/ast.html | ast — Abstract Syntax Trees — Python 3.7.4rc2 documentation
https://docs.python.org/3/library/ast.html#abstract-grammar | ast — Abstract Syntax Trees — Python 3.7.2 documentation	
https://docs.python.org/3/library/token.html | token — Constants used with Python parse trees — Python 3.7.4rc2 documentation

https://docs.python.org/3.7/library/parser.html | parser — Access Python parse trees — Python 3.7.4rc2 documentation
https://docs.python.org/3.6/library/parser.html#module-parse | 32.1. parser — Access Python parse trees — Python 3.6.9 documentation
https://docs.python.org/3/library/symtable.html | symtable — Access to the compiler’s symbol tables — Python 3.7.4rc2 documentation
-->

Code
* [Byte Code Wikipedia](https://en.wikipedia.org/wiki/Bytecode)
* [Object Code Wikipedia](https://en.wikipedia.org/wiki/Object_code)
* [Opcode Wikipedia](https://en.wikipedia.org/wiki/Opcode)
* [Opcode Table Wikipedia](https://en.wikipedia.org/wiki/Opcode_table)
* [Program Counter Wikipedia](https://en.wikipedia.org/wiki/Program_counter)

Method Resolution Order
* [C3 Linearization Wikipedia](https://en.wikipedia.org/wiki/C3_linearization)
* [Multiple Inheritance Wikipedia](https://en.wikipedia.org/wiki/Multiple_inheritance)
* [The Python 2.3 Method Resolution Order](https://www.python.org/download/releases/2.3/mro)

Avoiding Race Condition, Mutex or Semaphore, Global Interpreter Lock (GIL)
* [Race Condition- Software Wikipedia](https://en.wikipedia.org/wiki/Race_condition#Software)
* [Mutual Exclusion (Mutex) Wikipedia](https://en.wikipedia.org/wiki/Mutual_exclusion)
* [Semaphore Wikipedia](https://en.wikipedia.org/wiki/Semaphore_(programming))
* [Global Interpreter Lock (GIL) Wikipedia](https://en.wikipedia.org/wiki/Global_interpreter_lock)

Reference Counting and Garbage Collection
* [Reference Counting Wikipedia](https://en.wikipedia.org/wiki/Reference_counting)
* [Garbage Collection Wikipedia](https://en.wikipedia.org/wiki/Garbage_collection_(computer_science))

<!--
http://infolab.stanford.edu/~ullman/dragon/slides1.pdf | slides1.dvi
http://www.informatik.uni-bremen.de/agbkb/lehre/ccfl/Material/ALSUdragonbook.pdf | ALSUdragonbook.pdf
https://en.wikipedia.org/wiki/Source-to-source_compiler | Source-to-source compiler - Wikipedia
https://www.geeksforgeeks.org/compiler-design-construction-of-ll1-parsing-table/ | Compiler Design | Construction of LL(1) Parsing Table - GeeksforGeeks

https://github.com/python/cpython/blob/master/Lib/tokenize.py | cpython/tokenize.py at master · python/cpython

https://en.wikipedia.org/wiki/Backward_compatibility | Backward compatibility - Wikipedia
https://en.wikipedia.org/wiki/Namespace | Namespace - Wikipedia
https://en.wikipedia.org/wiki/Metaclass | Metaclass - Wikipedia
https://en.wikipedia.org/wiki/Memory_leak | Memory leak - Wikipedia
https://en.wikipedia.org/wiki/Circuit_(computer_science) | Circuit (computer science) - Wikipedia
https://en.wikipedia.org/wiki/Regular_expression | Regular expression - Wikipedia


https://www.geeksforgeeks.org/mutex-vs-semaphore/ | Mutex vs Semaphore - GeeksforGeeks
https://en.wikipedia.org/wiki/Virtual_machine#Process_virtual | Virtual machine - Wikipedia

New Style
https://www.python.org/doc/newstyle/ | New-style Classes | Python.org
https://docs.python.org/2/glossary.html#term-new-style-class | Glossary — Python 2.7.16 documentation
http://python-history.blogspot.com/2010/06/inside-story-on-new-style-classes.html

MRO
http://python-history.blogspot.com/2010/06/method-resolution-order.html
https://docs.python.org/3/library/stdtypes.html#class.__mro__

Super
https://docs.python.org/2/library/functions.html#super | 2. Built-in Functions — Python 2.7.16 documentation

http://python-history.blogspot.com/2009/04/metaclasses-and-extension-classes-aka.html

https://www.python.org/dev/peps/pep-0384/ | PEP 384 -- Defining a Stable ABI | Python.org


https://en.wikipedia.org/wiki/C_dynamic_memory_allocation

https://en.wikibooks.org/wiki/Category:Book:Microprocessor_Design | Category:Book:Microprocessor Design - Wikibooks, open books for an open world
https://en.wikibooks.org/wiki/Microprocessor_Design/Instruction_Decoder | Microprocessor Design/Instruction Decoder - Wikibooks, open books for an open world
https://en.wikipedia.org/wiki/Stack_machine | Stack machine - Wikipedia
https://en.wikipedia.org/wiki/Stack_machine#Virtual_stack_machines | Stack machine - Wikipedia

https://en.wikipedia.org/wiki/Short-circuit_evaluation | Short-circuit evaluation - Wikipedia

https://en.wikipedia.org/wiki/Free_variables_and_bound_variables | Free variables and bound variables - Wikipedia
https://en.wikipedia.org/wiki/Codec | Codec - Wikipedia


https://docs.python.org/2.0/ext/refcounts.html | 1.10 Reference Counts


Parse source code into a parse tree (Parser/pgen.c)
https://github.com/python/cpython/blob/master/Parser/pgen/pgen.py
Transform parse tree into an Abstract Syntax Tree
https://github.com/python/cpython/blob/master/Python/ast.c
Transform AST into a Control Flow Graph
https://github.com/python/cpython/blob/master/Python/compile.c
Emit bytecode based on the Control Flow Graph
https://github.com/python/cpython/blob/master/Python/compile.c

The grammar file for Python
https://github.com/python/cpython/blob/master/Grammar/Grammar
Numeric value of grammar rules
https://github.com/python/cpython/blob/master/Include/graminit.h
The list of types of tokens (literal tokens, such as :, numbers, etc.)
https://github.com/python/cpython/blob/master/Grammar/Tokens
Numeric value stored in
https://github.com/python/cpython/blob/master/Include/token.h
The parse tree is made up of node * structs as defined in
https://github.com/python/cpython/blob/master/Include/node.h
The definition of the AST nodes for Python is found in
https://github.com/python/cpython/blob/master/Parser/Python.asdl | cpython/Python.asdl at master · python/cpython
All code relating to the arena (memory management)
https://github.com/python/cpython/blob/master/Include/pyarena.h
https://github.com/python/cpython/blob/master/Python/pyarena.c
The AST is generated from the parse tree
https://github.com/python/cpython/blob/master/Python/ast.c
Constructor functions defined by the ASDL grammar and contained in Python/Python-ast.c (which was generated by Parser/asdl_c.py) to create the nodes of the AST. 
https://github.com/python/cpython/blob/master/Python/Python-ast.c
https://github.com/python/cpython/blob/master/Parser/asdl_c.py
Function and macros found in
https://github.com/python/cpython/blob/master/Python/asdl.c
https://github.com/python/cpython/blob/master/Include/asdl.h
AST to CFG to Bytecode
The conversion process is initiated... 
https://github.com/python/cpython/blob/master/Python/compile.c
The AST to CFG step is handled mostly by two functions... 
https://github.com/python/cpython/blob/master/Python/symtable.c
https://github.com/python/cpython/blob/master/Python/compile.c
Once the symbol table is created, it is time for CFG creation
https://github.com/python/cpython/blob/master/Python/compile.c
The official list of bytecode can be found
https://github.com/python/cpython/blob/master/Lib/opcode.py


https://github.com/python/cpython/blob/master/Programs/python.c
https://github.com/python/cpython/blob/master/Include/pymem.h
	
https://github.com/python/cpython/blob/master/Modules/main.c

https://github.com/python/cpython/blob/master/Python/ceval.c | cpython/ceval.c at master · python/cpython
https://github.com/python/cpython/blob/master/Include/opcode.h | cpython/opcode.h at master · python/cpython
https://docs.python.org/3/library/dis.html#opcode-collections | dis — Disassembler for Python bytecode — Python 3.7.3 documentation
https://github.com/python/cpython/blob/master/Python/pythonrun.c | cpython/pythonrun.c at master · python/cpython
https://github.com/python/cpython/blob/master/Python/pythonrun.c#L1063 | cpython/pythonrun.c at master · python/cpython

https://github.com/python/cpython/tree/master/Objects
https://github.com/python/cpython/blob/master/Include/object.h
https://github.com/python/cpython/blob/master/Objects/object.c

Protocols (similar to ABC)
https://github.com/python/cpython/blob/master/Include/abstract.h
https://github.com/python/cpython/blob/master/Objects/abstract.c


https://github.com/python/cpython/blob/master/Programs/python.c | cpython/python.c at master · python/cpython
https://github.com/python/cpython/blob/master/Include/object.h#L104 | cpython/object.h at master · python/cpython
https://github.com/python/cpython/blob/master/Python/ceval.c#L734 | cpython/ceval.c at master · python/cpython
https://github.com/python/cpython/blob/master/Python/pylifecycle.c | cpython/pylifecycle.c at master · python/cpython
https://github.com/python/cpython/blob/master/Parser/token.c | cpython/token.c at master · python/cpython
https://github.com/python/cpython/blob/master/Python/ceval.c#L4039 | cpython/ceval.c at master · python/cpython
https://github.com/python/cpython/blob/master/Objects/frameobject.c | cpython/frameobject.c at master · python/cpython
https://github.com/python/cpython/blob/master/Include/frameobject.h#L16 | cpython/frameobject.h at master · python/cpython
https://github.com/python/cpython/blob/master/Python/bltinmodule.c | cpython/bltinmodule.c at master · python/cpython



https://docs.python.org/3/reference/datamodel.html#customizing-class-creation | 3. Data model — Python 3.7.4rc2 documentation
https://docs.python.org/3/reference/datamodel.html#determining-the-appropriate-metaclass | 3. Data model — Python 3.7.4rc2 documentation


https://docs.python.org/3.6/c-api/typeobj.html#c.PyTypeObject.tp_traverse | Type Objects — Python 3.6.9 documentation
https://docs.python.org/3/library/python.html | Python Runtime Services — Python 3.7.4rc2 documentation
https://docs.python.org/3.7/c-api/memory.html | Memory Management — Python 3.7.4rc2 documentation
https://docs.python.org/3.6/c-api/typeobj.html | Type Objects — Python 3.6.9 documentation
https://docs.python.org/3/howto/descriptor.html | Descriptor HowTo Guide — Python 3.7.4rc2 documentation
https://docs.python.org/3.6/library/functions.html#compile | 2. Built-in Functions — Python 3.6.9 documentation

https://docs.python.org/3/extending/ | Extending and Embedding the Python Interpreter — Python 3.7.4rc1 documentation
https://docs.python.org/3/c-api/structures.html#c.PyObject | Common Object Structures — Python 3.7.4rc2 documentation
https://docs.python.org/3.6/using/cmdline.html | 1. Command line and environment — Python 3.6.9 documentation


Python and Django Source Code	

https://wiki.python.org/moin/DebuggingWithGdb | DebuggingWithGdb - Python Wiki
https://devguide.python.org/gdb/ | 22. gdb Support — Python Developer's Guide
https://www.gnu.org/software/gdb/ | GDB: The GNU Project Debugger

https://en.wikipedia.org/wiki/Unmarshalling | Unmarshalling - Wikipedia
https://docs.python.org/3/library/marshal.html | marshal — Internal Python object serialization — Python 3.7.3 documentation
https://github.com/python/cpython/blob/master/Python/marshal.c | cpython/marshal.c at master · python/cpython
-->

<!--	
https://fileinfo.com/extension/h | H File Extension - What is an .h file and how do I open it?	
https://docs.python.org/3/library/pkgutil.html | pkgutil — Package extension utility — Python 3.7.2 documentation	

$ python -m dis program.py	
compiler -> bytecode	
bytecode -> python interpreter (interpreter is written in C language)	
output	
(compiler/interpreter run together, bytecode is assembly language/instruction set, each bytecode is called an opcode)	
* Include/object.h	
* Objects/object.c	
* Python data model (Python API)	
* Python object protocol (C API)	

PyObject	
Frames, function calls, basic scope	
https://docs.python.org/2.4/lib/bytecodes.html	
https://docs.python.org/3/reference/datamodel.html#emulating-numeric-types
https://docs.python.org/3/c-api/ | Python/C API Reference Manual — Python 3.7.3 documentation
https://docs.python.org/3.7/c-api/object.html	
https://docs.python.org/3.7/c-api/structures.html	
https://docs.python.org/3.7/c-api/concrete.html		
https://docs.python.org/3.7/c-api/code.html	
https://docs.python.org/3/c-api/memory.html	
https://docs.python.org/2/c-api/int.html	
https://docs.python.org/2/c-api/type.html#c.PyTypeObject
https://docs.python.org/3.5//c-api/index.html
https://docs.python.org/3/c-api/structures.html#c.PyObject_HEAD
https://docs.python.org/3/c-api/structures.html#c.PyObject
PyTypeObject (52 members)
https://docs.python.org/3/c-api/typeobj.html

https://github.com/python/cpython/tree/master/Objects/clinic	
https://github.com/python/cpython/tree/master/Objects/stringlib	
-->

<!--
Abstract Syntax Trees

http://stackoverflow.com/questions/5026517/whats-the-difference-between-parse-tree-and-ast

ASDL, AST
https://eli.thegreenplace.net/2014/06/04/using-asdl-to-describe-asts-in-compilers | Using ASDL to describe ASTs in compilers - Eli Bendersky's website	

https://greentreesnakes.readthedocs.io | Green Tree Snakes - the missing Python AST docs — Green Tree Snakes 1.0 documentation	
https://greentreesnakes.readthedocs.io/en/latest/nodes.html | Meet the Nodes — Green Tree Snakes 1.0 documentation	
https://python-ast-explorer.com/ | Python AST Explorer	
-->

## Django Source

<!--
https://github.com/django/django/blob/master/django/core/handlers/base.py#L71 | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/core/handlers/base.py#L85 | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/urls/resolvers.py#L66 | django/resolvers.py at master · django/django
https://github.com/django/django/blob/master/django/template/context.py | django/context.py at master · django/django
https://github.com/django/django/blob/master/django/template/response.py | django/response.py at master · django/django
https://github.com/django/django/blob/master/django/http/__init__.py | django/__init__.py at master · django/django
https://github.com/django/django/blob/master/django/core/files/uploadhandler.py | django/uploadhandler.py at master · django/django

https://www.youtube.com/watch?v=tkwZ1jG3XgA | James Bennett - Django in Depth - PyCon 2015 - YouTube	
https://twitter.com/ubernostrum/status/1115023968925130752 | James Bennett on Twitter: "Let me know if you have questions. It's old/out-of-date, and tried to cover too much stuff (which is why I switched to doing an ORM-focused tutorial last year).… https://t.co/btm7lzK7rI"

Django Source Code
https://github.com/django/django/blob/master/django/__init__.py	
https://github.com/django/django/tree/master/django/apps	
https://github.com/django/django/blob/master/django/apps/config.py	
https://github.com/django/django/blob/master/django/apps/registry.py
https://github.com/django/django/blob/master/django/conf/__init__.py | django/__init__.py at master · django/django
https://github.com/django/django/blob/master/django/urls/conf.py	
https://github.com/django/django/blob/master/django/urls/resolvers.py
https://github.com/django/django/blob/master/django/middleware/common.py

https://github.com/django/django/blob/master/django/core/handlers/wsgi.py | django/wsgi.py at master · django/django
https://github.com/django/django/blob/master/django/http
https://github.com/django/django/blob/master/django/http/request.py | django/request.py at master · django/django	
https://github.com/django/django/blob/master/django/http/response.py	

https://github.com/django/django/blob/master/django/views/generic/__init__.py | django/__init__.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/base.py | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/base.py#L83 | django/base.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/detail.py | django/detail.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/list.py | django/list.py at master · django/django
https://github.com/django/django/blob/master/django/views/generic/list.py#L113	
	
https://github.com/django/django/blob/master/django/shortcuts.py
https://github.com/django/django/blob/master/django/core/exceptions.py	
	
https://github.com/django/django/tree/master/django/db/backends | django/django/db/backends at master · django/django	
https://github.com/django/django/blob/master/django/db/models/__init__.py 	
https://github.com/django/django/blob/master/django/db/models/query.py	
https://github.com/django/django/blob/master/django/db/models/query.py#L337	
https://github.com/django/django/blob/master/django/contrib/auth/base_user.py | 	
https://github.com/django/django/blob/master/django/db/models/lookups.py
-->
