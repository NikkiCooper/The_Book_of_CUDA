# 🌌 Genesis of a CUDA Program

---

## Verse 1: The Empty File
In the beginning, there was `main.cu`, and it was without code, and void.

---

## Verse 2: The First Include
And the Programmer said, “Let there be `#include <cuda_runtime.h>` and `#include <stdio.h>`,”  
And there was inclusion.

---

## Verse 3: The Kernel is Written
And the Programmer wrote the sacred kernel:

```c
__global__ void myKernel() {
    printf("Hello from thread %d!\n", threadIdx.x);
}
```

And it was good.

---

## Verse 4: The Launch
And the Programmer launched the kernel with:

```c
int main() {
    myKernel<<<1, 256>>>();
    cudaDeviceSynchronize();
    return 0;
}
```

And the threads multiplied across the SMs.

---

## Verse 5: The First Trial — *Psalm 4: The Psalm of Debugging* 🐞
Why hast thou forsaken me, O program?  
My kernels launch, yet my screen is but black.  
I cry unto thee with printf, but thou answerest not!

---

## Verse 6: The Output
And the Programmer copied the results back to host memory when needed,  
And beheld that the computation was correct.

---

## Verse 7: The Rest
And on the seventh compile, the Programmer rested,  
And the GPU fans spun down in peace.

---
[Next: Commandments of CUDA →](Commandments_Of_CUDA.md) • [Return ⬆ Table of Contents](README.md#-table-of-contents)
