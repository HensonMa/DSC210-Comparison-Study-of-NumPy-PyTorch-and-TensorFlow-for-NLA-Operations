# DSC210: Comparison Study of NumPy, PyTorch, and TensorFlow for NLA Operations

### Course: DSC 210: Numerical Linear Algebra
### Instructor: Dr. Lily Weng

#### Instructions:
- Ensure that the following libraries are installed in python 3 environment:
  - numpy
  - torch
  - tensorflow
  - matplotlib
  - scipy
  - psutil
  - gc
  - tracemalloc

- Ensure that CUDA is supported in your environment. 

- Open each jupyter notebook file accordingly for different matrix operations and run all the cells of the notebook.

### Results

#### Matrix Transpose

![210transpose](https://github.com/user-attachments/assets/87982c81-53ce-4115-a778-f5f85242cd79)

#### Matrix Multiplication

Single matrix multiplication on CPU
![single_mm_result](https://github.com/user-attachments/assets/95f75be9-9bc3-4b73-8bd3-7343bb2ce00b)

Nested matrix multiplication on CPU
![nested_mm_result](https://github.com/user-attachments/assets/65e4007d-0f52-4f38-82cb-c948b891ca71)

Repeated matrix multiplication on CPU
![repeated_mm_result](https://github.com/user-attachments/assets/187977e0-34f1-4af5-94a5-b0128c60d60b)

Single matrix multiplication on GPU
![single_mm_result_gpu](https://github.com/user-attachments/assets/e1ba2910-6afe-423b-a198-27409037a0b8)

Repeated matrix multiplication on GPU
![repeated_mm_result_gpu](https://github.com/user-attachments/assets/4065ed8f-ef05-45b9-94a2-7b01ae3a710f)

#### Eigenvalue decomposition (EVD)
Performance comparison of NumPy (CPU), PyTorch (GPU), and TensorFlow (GPU) for EVD on 2D matrices
<img width="671" alt="Screenshot 2024-12-10 at 1 14 52 PM" src="https://github.com/user-attachments/assets/0ed82d82-a7c8-4f94-925d-a75bfef4fc4b">

Computation time comparison for PyTorch and TensorFlow on CPU and GPU
<img width="725" alt="Screenshot 2024-12-10 at 1 14 34 PM" src="https://github.com/user-attachments/assets/0b3c2b31-8363-4e7d-87bd-66ebb0f22f34">

Performance comparison of NumPy, PyTorch, and TensorFlow for 3D matrix EVD (on CPU)
<img width="671" alt="EVD_results_3D" src="https://github.com/user-attachments/assets/0f0e0126-89a5-44d1-a1cc-6b06d96f7ce0">

#### Singular value decomposition (SVD)

Performance comparison of SVD implementations on dense matrices
![uniform](https://github.com/user-attachments/assets/0647d6fd-e42d-4667-882d-7a85ccb64e70)

Performance comparison of SVD implementations on sparse matrices
![sparse](https://github.com/user-attachments/assets/851ef2f2-349e-4056-bd4e-b5a341d3a44a)

