Awesome MLIR
============

A curated list of MLIR (Multi-Level Intermediate Representation) resources, tutorials, and dialects.

Official Tutorials
------------------

-   [Toy Tutorial](https://mlir.llvm.org/docs/Tutorials/Toy/) - The primary tutorial introducing MLIR concepts through implementing a toy language

-   [MLIR Tutorials Page](https://mlir.llvm.org/docs/Tutorials/) - Main tutorials section including Toy tutorial and Transform dialect tutorial

-   [Using mlir-opt](https://mlir.llvm.org/docs/Tutorials/MlirOpt/) - Command-line entry point for running passes and lowerings on MLIR code

-   [2020 LLVM Developers' Meeting MLIR Tutorial](https://www.youtube.com/watch?v=Y4SvqTtOIDk) - Video tutorial by Mehdi Amini & River Riddle

-   [MLIR For Beginners](https://github.com/j2kun/mlir-tutorial) - Step-by-step tutorial series covering build systems, passes, and dialect definition

Core Dialects
-------------

Built-in and Infrastructure
---------------------------

-   [builtin](https://mlir.llvm.org/docs/Dialects/Builtin/) - Core attributes, operations, and types with wide applicability

-   [func](https://mlir.llvm.org/docs/Dialects/) - Function definitions, declarations, call graphs, and inlining transformations

-   [cf](https://mlir.llvm.org/docs/Dialects/ControlFlowDialect/) - Low-level control flow constructs operating directly on SSA blocks

-   [llvm](https://mlir.llvm.org/docs/Dialects/LLVM/) - Maps LLVM IR into MLIR with corresponding operations and types

Arithmetic and Memory
---------------------

-   [arith](https://mlir.llvm.org/docs/Dialects/) - Basic mathematical operations over integers and floating-point types

-   [memref](https://mlir.llvm.org/docs/Dialects/) - Memory allocation and access operations

-   [tensor](https://mlir.llvm.org/docs/Dialects/) - Tensor operations and abstractions

-   [math](https://mlir.llvm.org/docs/Dialects/) - Mathematical functions and operations

Control Flow and Loops
----------------------

-   [scf](https://mlir.llvm.org/docs/Dialects/) - Structured control flow with for, if, and while constructs

-   [affine](https://mlir.llvm.org/docs/Dialects/Affine/) - Affine loop nests suitable for polyhedral optimization

-   [async](https://mlir.llvm.org/docs/Dialects/) - Asynchronous execution and concurrency primitives

Linear Algebra and Compute
--------------------------

-   [linalg](https://mlir.llvm.org/docs/Dialects/Linalg/) - High-level hierarchical optimization for linear algebra operations

-   [vector](https://mlir.llvm.org/docs/Dialects/) - SIMD vector operations and transformations

-   [gpu](https://mlir.llvm.org/docs/Dialects/GPU/) - GPU kernel launching and device management abstractions

Specialized Domains
-------------------

-   [tosa](https://mlir.llvm.org/docs/Dialects/) - Portable and quantization-friendly operator set for ML inference

-   [quant](https://mlir.llvm.org/docs/Dialects/) - Quantization support for machine learning models

-   [sparse_tensor](https://mlir.llvm.org/docs/Dialects/) - Sparse tensor operations and storage formats

Hardware-Specific
-----------------

-   [nvvm](https://mlir.llvm.org/docs/Dialects/) - NVIDIA GPU-specific operations and intrinsics

-   [rocdl](https://mlir.llvm.org/docs/Dialects/) - AMD GPU-specific operations for ROCm

-   [x86vector](https://mlir.llvm.org/docs/Dialects/) - x86-specific vector operations and intrinsics

Documentation
-------------

-   [MLIR Language Reference](https://mlir.llvm.org/docs/LangRef/) - Complete language specification and concepts

-   [Dialects Documentation](https://mlir.llvm.org/docs/Dialects/) - Comprehensive list of all available dialects

-   [Defining Dialects](https://mlir.llvm.org/docs/DefiningDialects/) - Guide for creating custom dialects

-   [Dialect Conversion](https://mlir.llvm.org/docs/DialectConversion/) - Framework for converting between dialects

Related Projects
----------------

-   [IREE](https://github.com/openxla/iree) - Retargetable MLIR-based machine learning compiler and runtime toolkit

-   [Torch-MLIR](https://github.com/llvm/torch-mlir) - First-class PyTorch ecosystem support for MLIR

-   [MLIR EmitC](https://github.com/iml130/mlir-emitc) - Conversions from MLIR to C/C++ code

-   [ONNX-MLIR](https://github.com/onnx/onnx-mlir) - Open-source compiler technology to transform ONNX graphs into optimized native code

-   [MLIR-TensorRT](https://github.com/NVIDIA/TensorRT-Incubator) - MLIR dialect that precisely models the TensorRT operator set with StableHLO conversions

-   [Mojo](https://github.com/oderoi/Mojo) - High-performance programming language combining Python usability with C performance via MLIR infrastructure

-   [BladeDISC](https://github.com/alibaba/BladeDISC) - Alibaba's end-to-end dynamic shape compiler for machine learning workloads based on MLIR infrastructure

-   [NVIDIA Tile IR](https://www.linkedin.com/posts/mehdiamini_mlir-activity-7308435907332747264--Kww) - NVIDIA's MLIR-based JIT compiler for tile-based programming in CUDA with cuTile DSL
