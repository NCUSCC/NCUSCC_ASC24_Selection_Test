# HPL
HPL是一个基础的高性能计算基准集，该基准集用于测试超算系统的算力，以FLOPS作为度量单位。最新版本的HPL用于对世界上最强大的超级计算机进行排名，构建全球超算TOP500榜单。HPL是HPLinpack的一个可移植实现，它用C语言编写，最初是作为一个指南，尽管可以使用其他技术和包，现在被广泛用于为TOP500列表提供数据。HPL生成一个n阶的线性方程组，并使用部分行枢轴的LU分解来解决它。它需要安装MPI和BLAS或VSIPL的实现来运行。