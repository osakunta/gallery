# gallery

A Pigallery2 configuration.

## Production setup

Before starting the service two symbolic links are needed: one to the root gallery directory and the other to the temp directory that will hold all the thumbnails etc. This can be accomplished with the following commands:

    ln -s [ROOT_GALLERY_DIRECTORY_PATH] images
    ln -s [TEMP_DIRECTORY_PATH] tmp

Run docker-compose in background:

    docker-compose up -d

Remember to add a proxy to the service (`localhost:8888`).
