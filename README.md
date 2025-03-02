# INCUS

As root

# Exploring
    
## List containers

    incus list

## Stop running instance
    
    incus stop container-name

## Delete insance
    
    incus delete container-name

## List available images
    
List debian images showing l:short alias, a:architecture, t:type s:size

    incus image list images:debian -clats


## Launch a container or vm

    incus launch images:debian/13  container-name

## Run a stopped container or vm

    incus start container-name

## Container info
    
    incus info container-name

## Run bash in container

   incus exec container-name -- bash 
