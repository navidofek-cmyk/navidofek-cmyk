*[English](#english) · [Čeština](#čeština)*

---

## English

# Process Engineering | CFD | Python Automation

Hands-on experience implementing CFD solvers for incompressible and compressible flow from the ground up. Work spans finite volume methods, shock-capturing schemes, pressure–velocity coupling, and Python-based workflow automation.

Focus is on understanding what happens inside the solver — not just running simulations.

### Skills

**CFD & Numerics**
- Incompressible: projection methods, SIMPLE, PISO, staggered MAC grids
- Compressible: Euler equations, exact Riemann solver, Rusanov, HLLC flux schemes, MUSCL reconstruction
- Discretisation: FDM, FVM (cell-centred and staggered), structured Cartesian meshes
- Turbulence: RANS closure
- Post-processing: VTK output, ParaView

**Implementation**
- C++ solver development — no external dependencies, standard library only
- Python for pre/post-processing, parametric runs, and result parsing
- Async task pipelines for distributed compute workflows
- Docker, Kubernetes, gRPC, FastAPI

**Geometry**
- NURBS curve evaluation and derivative computation

### Projects

| Repository | What it is |
|---|---|
| [Programming_CFD_cases_tutorial](https://github.com/navidofek-cmyk/Programming_CFD_cases_tutorial) | 12 standalone C++ solvers — from lid-driven cavity to RANS airfoil. No dependencies. |
| [nurbs-minimal](https://github.com/navidofek-cmyk/nurbs-mininimal) | Minimal NURBS curve library for geometry and mesh work |
| [flowcore-async-orchestrator](https://github.com/navidofek-cmyk/flowcore-async-orchestrator) | DAG-based async task engine — designed for distributed simulation pipelines |
| [ai-compute-platform](https://github.com/navidofek-cmyk/ai-compute-platform) | Python/C++ microservice platform with gRPC compute backend |

### Contact

[i.dofek@seznam.cz](mailto:i.dofek@seznam.cz) · [github.com/navidofek-cmyk](https://github.com/navidofek-cmyk)

---

## Čeština

# Procesní inženýrství | CFD | Python automatizace

Praktické zkušenosti s implementací CFD solverů pro nestlačitelné i stlačitelné proudění od základů. Práce zahrnuje metody konečných objemů, schémata pro zachycení rázových vln, vazbu tlak–rychlost a automatizaci workflow v Pythonu.

Důraz na pochopení toho, co se děje uvnitř solveru — ne pouze spouštění simulací.

### Dovednosti

**CFD a numerika**
- Nestlačitelné proudění: projekční metody, SIMPLE, PISO, posunuté MAC sítě
- Stlačitelné proudění: Eulerovy rovnice, přesný Riemannův solver, Rusanov, HLLC, MUSCL rekonstrukce
- Diskretizace: MKD, MKO (cell-centred i staggered), strukturované kartézské sítě
- Turbulence: RANS uzávěr
- Post-processing: VTK výstup, ParaView

**Implementace**
- Vývoj solverů v C++ — bez externích závislostí, pouze standardní knihovna
- Python pro pre/post-processing, parametrické výpočty a zpracování výsledků
- Asynchronní task pipelines pro distribuované výpočetní workflow
- Docker, Kubernetes, gRPC, FastAPI

**Geometrie**
- Výpočet NURBS křivek a jejich derivací

### Projekty

| Repozitář | Popis |
|---|---|
| [Programming_CFD_cases_tutorial](https://github.com/navidofek-cmyk/Programming_CFD_cases_tutorial) | 12 samostatných C++ solverů — od lid-driven cavity po RANS airfoil. Bez závislostí. |
| [nurbs-minimal](https://github.com/navidofek-cmyk/nurbs-mininimal) | Minimální NURBS knihovna pro geometrii a tvorbu sítí |
| [flowcore-async-orchestrator](https://github.com/navidofek-cmyk/flowcore-async-orchestrator) | Asynchronní task engine na bázi DAG pro distribuované simulační pipelines |
| [ai-compute-platform](https://github.com/navidofek-cmyk/ai-compute-platform) | Python/C++ microservice platforma s gRPC výpočetním backendem |

### Kontakt

[i.dofek@seznam.cz](mailto:i.dofek@seznam.cz) · [github.com/navidofek-cmyk](https://github.com/navidofek-cmyk)
