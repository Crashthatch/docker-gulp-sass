As [/zenoss/gulp](https://github.com/zenoss/gulp), but with added global gulp-sass!

See [parent image's README.md](https://github.com/zenoss/gulp) for details: 

##Example Usage
    #do gulp sass task:
    docker run --rm -v $(pwd)/:/mnt/ -e UID=$(id -u) -e GID=$(id -g) crashthatch/gulp-sass gulp sass