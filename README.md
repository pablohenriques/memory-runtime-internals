# Memory & Runtime Internals — Guias Visuais

Uma coleção de guias visuais e interativos sobre como linguagens de programação gerenciam memória, organizam a execução e funcionam por dentro. Cada documento explora a arquitetura interna de uma linguagem de forma visual e acessível, em **Português**.

## Documentos disponíveis

| Guia | Linguagem | Tópicos |
|------|-----------|---------|
| [go-memory.html](go-memory.html) | Go | Stack, Heap, Goroutines, GC tricolor |
| [go-runtime.html](go-runtime.html) | Go | Scheduler M:N, Work stealing, Stack growth |
| [go-runtime-visual.html](go-runtime-visual.html) | Go | Simulação interativa: GMP, channels, syscall |
| [js-engine.html](js-engine.html) | JavaScript | Call stack, Event loop, Microtasks, V8 |
| [jvm-memory.html](jvm-memory.html) | Java / JVM | Heap geracional, JIT, Bytecode, Metaspace |
| [python-internals.html](python-internals.html) | Python / CPython | Ref counting, GIL, pymalloc, Cyclic GC |
| [rust-memory.html](rust-memory.html) | Rust | Ownership, Borrowing, Lifetimes, Zero-cost |
| [swift-memory.html](swift-memory.html) | Swift | ARC, Weak/Unowned, Retain cycles, Value types |

## Tópicos cobertos

- Garbage Collection (GC tricolor, heap geracional, cyclic GC)
- Ownership & Borrowing (Rust)
- ARC — Automatic Reference Counting (Swift)
- JIT Compilation (JVM, V8)
- Event Loop e Call Stack (JavaScript)
- Goroutines e Scheduler M:N (Go)
- GIL — Global Interpreter Lock (Python)
- Stack Frames e Heap Allocation
- Contagem de referências

## Público-alvo

Desenvolvedores que já conhecem a linguagem mas querem entender o que acontece *por debaixo dos panos* — do código-fonte até os registradores da CPU.

## Como usar

Abra o [index.html](index.html) no navegador para acessar o portal com todos os guias, ou abra diretamente o arquivo HTML da linguagem de interesse.

Não há dependências externas além de fontes carregadas via Google Fonts. Todos os guias funcionam offline após o primeiro carregamento.
