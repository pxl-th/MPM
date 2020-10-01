# MPM

Material-Point-Methods in Julia.

Files in `src` contain different implementations of MPM for different materials.

Each example is self contained and should run as is (provided you have installed necessary packages).

| Fluid simulation | Elasticity |
|:-:|:-:|
| [YouTube](https://www.youtube.com/watch?v=O8cXswg9xHw)  | [YouTube](https://www.youtube.com/watch?v=B2dO3poS5PA) |
|<img src="https://img.youtube.com/vi/O8cXswg9xHw/hqdefault.jpg" alt="Fluid simulation" width="200"/>|<img src="https://img.youtube.com/vi/B2dO3poS5PA/hqdefault.jpg" alt="Elasticity" width="200"/> |

## Run

Julia 1.5 or above is needed.

Fluid simulation supports multithreading, so `-t4` flag actually makes difference.

```bash
julia -t4 --project=. src/fluid.jl 
```

## References

- Great niall's MLS-MPM [guide](https://nialltl.neocities.org/articles/mpm_guide.html).
- Taichi MPM [github](https://github.com/yuanming-hu/taichi_mpm).
