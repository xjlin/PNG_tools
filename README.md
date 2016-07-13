# install a bunch of PNG tools on mac

pngcrush
    
    mac,linux通用
    cd pngcrush-1.8.1
    make
    sudo mv pngcrush /usr/local/bin/
    
pngout
    
    进linux或者mac相对应的文件夹
    sudo mv pngout /usr/local/bin/
    
optipng

    centOS:
    cd /tmp/; wget http://pkgs.repoforge.org/optipng/optipng-0.6.4-1.el6.rf.x86_64.rpm
    yum localinstall optipng-0.6.4-1.el6.rf.x86_64.rpm -y
    mac:
    brew install opting
    
advancecomp(include advdef, advpng......)

    cd advancecomp-1.20
    sudo ./configure
    sudo make install
    
jpegoptim

    centOS:
    cd jpegoptim-1.3.0-centOS
    ./configure
    make
    make strip
    make install
    mac:
    brew install jpegoptim

