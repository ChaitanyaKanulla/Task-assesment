# Task-assesment

We can do the task in various ways simple writing a small programm using any programming language to build a simple rest application so i thought instead of creating in this way again we need to keep in container thats i took docker image directly from docker hub which is having a simple rest application 

WE can also use lambda functions to call rest api and build a simple application 

We can also create using terraform infra provisioning container and image will deploy on k8s .After that create pod,services(loadbalancer&autoscaling) and creating a pipeline job from gitlab if the pipeline is sucess it will automatically deploy in k8s 


But my approach is created a simple application and kept that application (container) in kubernetes and created services and ensured the seurity measures as well created a horizontal autoscaling to balance the cpu usage and created a pipeline in gitlab and triggered with gitlab runner it will automatically do the changes in k8s .

Thankyou apologies for submitting late i was strucked at some personal problems if i get a chance to aything in the sameway end to end im always stand in front line .
