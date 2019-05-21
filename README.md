# googlecontainertools-jib
builds optimized docker and oci images for youre java applications 
without a docker daemon and without deep mastery of docker best practices.it is available as plugins for maven and gradle and as a java library.
how jib works>>> whereas traditionally a java application is built as a single image layer with the application jar,jibs builds stragety seperates the java application into multiple layers for more granular incremental builds.when you change your code only your changes are rebuilt not your intire application.these layers by default are layered on top of a distroless base image.
