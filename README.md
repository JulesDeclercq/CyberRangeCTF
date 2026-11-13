# Cyber Range & CTF

## Handige gegevens

**container:**
user: student
passwd: student123

> Om container te starten als student
`docker run -it --user student debian_modified:latest`
> Om uit de shell van de container the gaan
Ctrl+p, Ctrl+q
> Om image op te slaan
`docker commit <container-id> debian_modified`
> Om container te stoppen
`docker stop <container-id>`
> Om terug in draaiende container aan de shell te geraken
`docker attach <container-id>`
