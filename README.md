# GFBR MEM Inversion

A computational framework for recovering distributions from dynamic light scattering (DLS) correlation data using maximum entropy methods.

The project was developed to investigate the behaviour and limitations of maximum entropy inversion for ill-posed exponential-decay problems. It includes the theoretical formulation, numerical implementation, validation using experimental and simulated data, and supporting Mathematica tools.

## Repository structure

### `example/`

A minimal working example using experimental BSA dynamic light scattering data.

The example includes:

- `gfbr-mem_example.nb` — Mathematica notebook demonstrating the analysis
- `gfbr-mem_example.pdf` — PDF version of the example
- `dls_mem_functions.nb` — GFBR MEM implementation
- `helper_functions.nb` — supporting Mathematica functions
- `dls_mass_phot_bsa.txt` — example experimental dataset

### `docs/`

Detailed documentation of the development and validation of the method:

- `gfbr_mem_theory.pdf` — theoretical formulation
- `gfbr_mem_principle.pdf` — development, numerical investigation, and validation
- `gfbr_mem_functions.pdf` — GFBR MEM function documentation
- `helper_functions.pdf` — supporting Mathematica function library

## Example

The example demonstrates the workflow from experimental correlation data to a recovered distribution:

`g₂ data → preprocessing → g₁ data → constrained MEM inversion → recovered distribution`

See `example/gfbr-mem_example.pdf` for a short readable demonstration or `example/gfbr-mem_example.nb` for the executable Mathematica notebook.

## Implementation

The current reference implementation is written in Wolfram Mathematica. A Python implementation is under development.
