# 📌 Phase 1 — Master Python (1–2 Months)

## 🐍 Core Language

### Decorators
- [ ] Function decorators
- [ ] Class decorators
- [ ] Decorators with arguments
- [ ] @functools.wraps and why it matters
- [ ] Stacking multiple decorators
- [ ] Real-world use cases: @timer, @retry, @cache, @validate

### Closures
- [ ] Lexical scoping
- [ ] nonlocal keyword
- [ ] Factory functions using closures
- [ ] Closures vs classes for state

### Context Managers
- [ ] `with` statement mechanics (__enter__ / __exit__)
- [ ] @contextmanager decorator
- [ ] Resource management (files, connections, locks)
- [ ] Nested context managers
- [ ] Async context managers

### Iterators & Generators
- [ ] Iterator protocol (__iter__ / __next__)
- [ ] Generator functions (yield)
- [ ] Generator expressions
- [ ] yield from (delegation)
- [ ] Infinite generators
- [ ] Memory-efficient data pipelines
- [ ] itertools module (chain, islice, groupby, product, combinations)

### Comprehensions
- [ ] List comprehensions
- [ ] Dict comprehensions
- [ ] Set comprehensions
- [ ] Nested comprehensions
- [ ] When NOT to use comprehensions (readability)

### Descriptors
- [ ] __get__, __set__, __delete__
- [ ] __set_name__
- [ ] Data vs non-data descriptors
- [ ] How property() works under the hood
- [ ] Validation descriptors
- [ ] Lazy-loading descriptors

### Metaclasses
- [ ] type() as a metaclass
- [ ] __new__ vs __init__ in metaclasses
- [ ] __init_subclass__ (simpler alternative)
- [ ] Class registries
- [ ] When to use metaclasses vs decorators vs __init_subclass__

### Dataclasses
- [ ] @dataclass decorator
- [ ] field() and default_factory
- [ ] frozen dataclasses (immutability)
- [ ] __post_init__
- [ ] Inheritance with dataclasses
- [ ] dataclass vs NamedTuple vs TypedDict

### Enums
- [ ] Basic Enum
- [ ] IntEnum, StrEnum
- [ ] auto() values
- [ ] Flag enums
- [ ] Enum methods and properties

### Magic Methods (Dunder Methods)
- [ ] __repr__ vs __str__
- [ ] __eq__, __hash__, __lt__ (comparison)
- [ ] __add__, __mul__ (arithmetic)
- [ ] __getitem__, __setitem__ (container)
- [ ] __call__ (callable objects)
- [ ] __slots__ (memory optimization)

---

## 📝 Typing & Validation

### Type Hints
- [ ] Basic types (int, str, list, dict)
- [ ] Optional, Union, Any
- [ ] Type aliases
- [ ] Literal types
- [ ] TypeVar (generics)
- [ ] Generic classes
- [ ] Protocols (structural typing)
- [ ] @overload
- [ ] TypeGuard
- [ ] Running mypy / pyright

### Pydantic
- [ ] BaseModel
- [ ] Field validators (@field_validator)
- [ ] Model validators (@model_validator)
- [ ] Nested models
- [ ] Custom types
- [ ] Settings management (BaseSettings)
- [ ] Serialization (model_dump, model_json_schema)
- [ ] Pydantic v2 vs v1 differences

---

## ⚡ Performance & Concurrency

### Threading
- [ ] Thread creation and management
- [ ] Thread pools (concurrent.futures.ThreadPoolExecutor)
- [ ] Locks, RLocks, Semaphores
- [ ] Thread-safe data structures (queue.Queue)
- [ ] When to use threading (I/O-bound tasks)

### Multiprocessing
- [ ] Process creation
- [ ] Process pools (ProcessPoolExecutor)
- [ ] Shared memory
- [ ] Inter-process communication (Pipes, Queues)
- [ ] When to use multiprocessing (CPU-bound tasks)

### AsyncIO
- [ ] async/await syntax
- [ ] Event loop
- [ ] Coroutines vs Tasks
- [ ] asyncio.gather, asyncio.wait
- [ ] Async generators
- [ ] Async context managers
- [ ] aiohttp / httpx for async HTTP
- [ ] Async database drivers (asyncpg)
- [ ] Semaphores for rate limiting

### GIL (Global Interpreter Lock)
- [ ] What it is and why it exists
- [ ] How it affects threading
- [ ] Workarounds (multiprocessing, C extensions, sub-interpreters)
- [ ] Python 3.13+ free-threading experiment

### Profiling
- [ ] cProfile / profile
- [ ] line_profiler
- [ ] memory_profiler
- [ ] tracemalloc
- [ ] py-spy (sampling profiler)
- [ ] Identifying bottlenecks

---

## 🛡️ Error Handling & Logging

- [ ] Exception hierarchy
- [ ] Custom exception classes
- [ ] Exception chaining (from e)
- [ ] Logging module (levels, formatters, handlers)
- [ ] Structured logging (structlog / python-json-logger)
- [ ] Retry logic (tenacity library)
- [ ] Circuit breaker pattern
- [ ] Graceful degradation

---

## 🧪 Testing

### Pytest
- [ ] Test discovery and conventions
- [ ] Assertions and matchers
- [ ] Fixtures (scope, autouse, yield fixtures)
- [ ] Parametrize (test multiple inputs)
- [ ] Markers (skip, xfail, custom markers)
- [ ] conftest.py

### Mocking
- [ ] unittest.mock (Mock, MagicMock, patch)
- [ ] Mocking external APIs
- [ ] Mocking database calls
- [ ] When to mock vs when to use real dependencies

### Integration Testing
- [ ] Testing with real database (testcontainers)
- [ ] Testing with real Redis
- [ ] API integration tests
- [ ] Test database setup/teardown

### Load Testing
- [ ] Locust basics
- [ ] Writing load test scenarios
- [ ] Interpreting results (p50, p95, p99 latency)

### Code Quality
- [ ] Coverage (pytest-cov)
- [ ] Ruff (linting + formatting)
- [ ] pre-commit hooks
- [ ] Type checking in CI

---

## 🚀 Phase 1 Projects

- [ ] **Concurrent Web Crawler** — async, rate limiting, retry logic, data persistence
- [ ] **File Processing Pipeline** — generators, multiprocessing, progress tracking
