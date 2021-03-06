= Abstract =
Do you run your containers as root, or as a regular user? It’s such a deceptively simple question. You might be tempted to answer too quickly. Is the threat model really crystal clear in your mind? I have a suspicion that it might not be. This workshop is intended to help clarify.

Before you can answer the question above, you need to determine if we are talking about the container engine (Podman, Docker, CRI-O, containerd, etc), the process inside of the container (apache, postgresql, mysql, etc) or the process ID the container is mapped to (all three can be different). At first glance, this might not be obvious. Either the container engine or its sub-process in containers can be run as virtually any user. This workshop will walk through understanding root inside and outside the container so that you can better model threads, risks and mitigation with containers.

= Source Material =
* Schedule: https://devconfcz2021.sched.com/event/gmSP/understanding-root-inside-and-outside-a-container
* Presentation: https://docs.google.com/presentation/d/1tLAWFnrjdRGl3TCzHrPzfU3FQFeixJe7HgzSAom9ej0
