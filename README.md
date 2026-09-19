````md
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0D1117&height=100&section=header"/>

# M/OS

### MATHEUS CANTARUTTI

`ENGINEERING ENVIRONMENT`

**Engineering systems that make data reliable.**

<br>

[ LinkedIn ] · [ GitHub ] · [ YouTube ] · [ Medium ]

</div>

---

```text
┌──────────────────────────────────────────────────────────────────────┐
│ M/OS :: BOOT SEQUENCE                                               │
├──────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  user        matheus                                                 │
│  role        data-engineer                                           │
│  environment data · software · systems                               │
│                                                                      │
│  loading engineering modules...                                     │
│                                                                      │
│  [✓] data-engineering                                                │
│  [✓] software-engineering                                            │
│  [✓] data-platform                                                   │
│  [✓] automation                                                      │
│  [✓] data-quality                                                    │
│  [✓] observability                                                   │
│                                                                      │
│  system status ........................................ ONLINE       │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
````

<br>

## `~/system`

```text
┌──────────────────────────────────────────────────────────────────────┐
│ SYSTEM                                                               │
├──────────────────────────────────────────────────────────────────────┤
│                                                                      │
│  DATA                                                                │
│  ├── ingestion                                                       │
│  ├── transformation                                                  │
│  ├── modeling                                                        │
│  └── validation                                                      │
│                                                                      │
│  SOFTWARE                                                            │
│  ├── architecture                                                    │
│  ├── backend                                                          │
│  ├── automation                                                       │
│  └── developer-experience                                             │
│                                                                      │
│  PLATFORM                                                            │
│  ├── pipeline execution                                               │
│  ├── permissions                                                      │
│  ├── observability                                                    │
│  └── reusable components                                              │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

I work at the intersection of **data engineering and software engineering**, with a particular interest in the systems that make data workflows reliable, maintainable and scalable.

---

![perfil](https://github.com/cantaruttim/cantaruttim/blob/main/assets/perfil)

---

## `~/processes`

```text
┌──────┬─────────────────────────┬─────────────┬──────────────────────┐
│ PID  │ PROCESS                 │ STATE       │ RUNTIME              │
├──────┼─────────────────────────┼─────────────┼──────────────────────┤
│ 001  │ data-platform           │ BUILDING    │ Java · Python · Spark │
│ 002  │ pipeline-engineering    │ ACTIVE      │ PySpark · SQL         │
│ 003  │ data-quality             │ ACTIVE      │ SQL · dbt             │
│ 004  │ workflow-engineering    │ EXPLORING   │ Kedro                 │
│ 005  │ engineering-lab         │ EXPLORING   │ Systems · Architecture│
└──────┴─────────────────────────┴─────────────┴──────────────────────┘
```

### `PID 001 — data-platform`

```text
STATUS      BUILDING

PURPOSE
Create a modular environment where engineers can
build, execute and manage their own data pipelines.

CURRENT EXPLORATION
├── pipeline execution
├── permissions
├── reusable components
├── data processing
└── developer experience
```

### `PID 002 — pipeline-engineering`

```text
STATUS      ACTIVE

FOCUS
Reliable and maintainable data workflows.

TOOLS
Python · PySpark · SQL · Spark
```

### `PID 003 — data-quality`

```text
STATUS      ACTIVE

FOCUS
Validation, testing and confidence in data products.

TOOLS
SQL · dbt · Python
```

---

## `~/architecture`

```text
                         DATA SYSTEM

 SOURCE
   │
   ▼
┌──────────┐
│ INGESTION│
└────┬─────┘
     │
     ▼
┌──────────────┐
│ TRANSFORMATION│
└──────┬───────┘
       │
       ├───────────────┐
       ▼               ▼
  ┌─────────┐    ┌──────────────┐
  │ QUALITY │    │ OBSERVABILITY│
  └────┬────┘    └──────┬───────┘
       │                │
       └────────┬───────┘
                ▼
         ┌─────────────┐
         │ TRUSTED DATA│
         └──────┬──────┘
                │
                ▼
          BUSINESS / APPS
```

The pipeline is only one part of the system.

The engineering around it matters too.

---

## `~/stack`

```text
┌──────────────────────────────────────────────────────────────────────┐
│ RUNTIME                                                              │
│                                                                      │
│ Python        ████████████████████                                   │
│ SQL           ████████████████████                                   │
| Java          █████████████░░░░░░░                                  │
│                                                                      |
│                                                                      │
├──────────────────────────────────────────────────────────────────────┤
│ DATA                                                                 │
│                                                                      │
│ Spark         ███████████████████░                                   │
│ PySpark       ███████████████████░                                   │
│ Databricks    █████████████████░░░                                   │
│ DuckDB        ████████████████░░░░                                   │
│ PostgreSQL    ███████████████░░░░░                                   │
│                                                                      │
├──────────────────────────────────────────────────────────────────────┤
│ DATAOPS                                                              │
│                                                                      │
│ dbt           █████████████████░░░                                   │
│ Kedro         ███████████████░░░░░                                   │
│ Testing       ████████████████░░░░                                   │
│ Quality       █████████████████░░░                                   │
│                                                                      │
├──────────────────────────────────────────────────────────────────────┤
│ ENGINEERING                                                          │
│                                                                      │
│ Git           ████████████████████                                   │
│ Docker        █████████████████░░░                                   │
│ Linux         ███████████████████░                                   │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

---

## `~/projects`

```text
$ ls -la projects/

drwxr-xr-x  data-platform
drwxr-xr-x  data-engineering
drwxr-xr-x  engineering-lab
drwxr-xr-x  personal-finance
```

### `data-platform`

A personal engineering project exploring the design of a modular data platform.

`Java` · `Python` · `Spark` · `DataOps` · `Architecture`

### `data-engineering`

Experiments with data pipelines, transformation, orchestration and quality.

`PySpark` · `dbt` · `Kedro` · `DuckDB`

### `engineering-lab`

A space for exploring software engineering concepts applied to data systems.

`Architecture` · `Distributed Systems` · `Backend` · `Developer Experience`

---

## `~/config/engineering.yml`

```yaml
engineering:

  simplicity:
    preferred: true

  automation:
    repeatable_work: automate

  quality:
    validation: explicit
    testing: continuous

  observability:
    pipelines: observable
    failures: actionable

  architecture:
    coupling: minimize
    components: reusable

  development:
    documentation: useful
    experimentation: encouraged
```

---

## `~/status`

```text
┌──────────────────────────────────────────────────────────────────────┐
│                                                                      │
│  DATA ENGINEERING       ● ACTIVE                                     │
│  SOFTWARE ENGINEERING   ● ACTIVE                                     │
│  DATA PLATFORM          ● BUILDING                                   │
│  DATAOPS                 ● ACTIVE                                     │
│  DISTRIBUTED SYSTEMS    ○ EXPLORING                                  │
│  CLOUD ENGINEERING      ○ EXPLORING                                  │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘
```

---

## `~/philosophy`

```text
BUILD
  │
  ▼
AUTOMATE
  │
  ▼
VALIDATE
  │
  ▼
OBSERVE
  │
  ▼
IMPROVE
```

> Good engineering is not only about making something work.
> It is about making it understandable, repeatable and reliable.

---

<div align="center">

<br>

### M/OS

`DATA` · `SYSTEMS` · `ENGINEERING`

<br>

**Always building. Always improving.**

<br>

[ LinkedIn ] · [ YouTube ] · [ Medium ]

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0D1117&height=100&section=footer"/>

</div>
```
