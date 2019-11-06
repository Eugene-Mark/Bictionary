## Alluxio
Alluxio is a memory centric, distributed storage system resides between computed layer and storage layer.
It's open sourced and initiated from UC berkley, AMP lab. 

###
Core modules
 - Master: metadata modification
 - Worker: transfer data in and our from underlying system
 - Client: compute layer use client to communicate with Alluxio server ( master and worker )
 - Job master & job worker: job scheduling
