# linux-commands

-- tar -xvzf community_images.tar.gz

To explain a little further, tar collected all the files into one package, community_images.tar. The gzip program applied compression, hence the gz extension. So the command does a couple things:

    f: this must be the last flag of the command, and the tar file must be immediately after. It tells tar the name and path of the compressed file.
    z: tells tar to decompress the archive using gzip
    x: tar can collect files or extract them. x does the latter.
    v: makes tar talk a lot. Verbose output shows you all the files being extracted.
