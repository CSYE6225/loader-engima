# loader-engima
This repo will include loader components for both offline and online workloads.
The offline will sort based. We will generate a radnom file and ask a server component (using PHP) to sort it. 
The random file will be based on the baseline we agree on. e.g.,  
dd if=/dev/urandom of=1.log bs=5M count=2
The server will load the generated file 1.log and sort it. 
Our loader system will deploy the files across the compute system and log the processsing time.

