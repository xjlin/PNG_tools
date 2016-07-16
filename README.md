# install a bunch of PNG tools on OSX or CentOS(need root)

pngcrush(available for OSX and CentOS)
    
    cd pngcrush-1.8.1
    make
    sudo mv pngcrush /usr/local/bin/
    
pngout
    
    cd pngout-yourOS
    sudo mv pngout /usr/local/bin/
    
optipng

    CentOS:
    cd /tmp/; wget http://pkgs.repoforge.org/optipng/optipng-0.6.4-1.el6.rf.x86_64.rpm
    yum localinstall optipng-0.6.4-1.el6.rf.x86_64.rpm -y

    OSX:
    brew install opting
    
advancecomp(include advdef, advpng......)

    CentOS:
    cd advancecomp-1.17-CentOS
    ./configure
    make
    make install

    OSX:
    cd advancecomp-1.20
    sudo ./configure
    sudo make install
    
jpegoptim

    CentOS:
    cd jpegoptim-1.3.0-CentOS
    yum install libjpeg-devel
    ./configure
    make
    make strip
    make install

    OSX:
    brew install jpegoptim

gifsicle(only for CentOS)

    cd /tmp/; wget http://pkgs.repoforge.org/gifsicle/gifsicle-1.68-1.el6.rf.x86_64.rpm
    yum localinstall gifsicle-1.68-1.el6.rf.x86_64.rpm -y

svgo(only for CentOS)

    npm install -g svgo