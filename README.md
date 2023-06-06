# Dynamic-Allocator

During this project, I successfully developed and implemented a robust and efficient dynamic memory allocator designed to replace the standard malloc() calloc() realloc() and free() function for heap memory in a Unix process, capable of running vim. This endeavor allowed me to gain valuable insights into the realm of dynamic memory management, pointer manipulation, and pointer casting.

To achieve this, I utilized a pool allocator approach, employing multiple memory pools. Each memory pool consisted of fixed-size allocations, catering to a range of memory requirements from 32 bytes to 4096 bytes. By adopting this strategy, I ensured optimal memory utilization and allocation efficiency within the Unix process.

The project involved leveraging the operating system system call sbrk(). These system calls played a crucial role in manipulating the program break between the application's heap and the unmapped memory region above it.

Throughout the implementation of the dynamic memory allocator, I demonstrated my proficiency in memory management techniques, precision in pointer manipulation, and adeptness in pointer casting. The project showcased my ability to create a reliable and efficient solution for memory allocation, significantly enhancing the overall performance of Unix processes.

Overall, this project provided valuable experience in implementing a pool allocator and utilizing system calls for managing the program break, thereby improving dynamic memory allocation in Unix environments.

