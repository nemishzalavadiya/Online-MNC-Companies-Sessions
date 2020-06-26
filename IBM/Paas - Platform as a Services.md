**Paas ( Platform as a Service )**

>cloud

- servers put together to provide services

> cloud computing models ( to leverage services )

- Iaas ( own house ) rents the servers and storage
- Paas ( what we need - os / tools etc. ) ( build own application )
  ex.   microsoft azure, IBM red-hat
- Saas ( use others service  )  ( use others applications in ours ) 
  ex.   gamil
  
>Cloud deployment

- public : multiple organizations
- private : dedicated to one organization
- hybrid : mix up

> Virtualization

- Hypervisor ( guest operating systems/ I-O/ CPU / RAM ) ( VM hardware )

>Containerization

- virtual machines creates guest os while in container it's not an issue, container Daemon handles it.no need of Hypervisor becuase or container daemon
- container comprises of all the libraries and os needed for applications

> Docker image

- Docker is a platform which puts dependencies and applications packages togther and forms container.
- Docker Images immutable ( contains every thing to run an applications )
- Docker Container running instance of Docker image.

>Image Stream : collection of images ( Docker formatted container images identified by tags ) 
  - eg. Docker hub 

>Build Config : how to create container ? is it using git hub or docker image

>Deployment config :  # of container? how much to scale up/down.

>CI/CD pipeline ( CD - Continuos Deployment/ CI - Continuous Integration )
 - automate steps in software delivery testing, enable fast product iterations.

>Container Orchestration ( load balancing, deployment managing automation )
 - kubernetes ( Google ) ( meant for single users )
 - open shift ( it's for organize category ) 

**Docker Contaniner -> kubernetes -> tools** [ Path of Development ]
